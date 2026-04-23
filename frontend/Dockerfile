# =========================
# Etapa 1: Build
# =========================
FROM node:latest AS build

WORKDIR /app

# Copia apenas os arquivos de dependência (melhora cache)
COPY package*.json ./
RUN npm install

# Copia o restante do projeto
COPY . .

# Executa o build (astro build)
RUN npm run build


# =========================
# Etapa 2: Produção
# =========================
FROM nginx:alpine

# Remove config default (opcional)
RUN rm /etc/nginx/conf.d/default.conf

# Copia arquivos estáticos gerados pelo Astro
COPY --from=build /app/dist /usr/share/nginx/html

# Copia configuração customizada do nginx (opcional)
# COPY nginx.conf /etc/nginx/conf.d/default.conf

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]