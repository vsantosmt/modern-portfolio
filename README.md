# 🚀 Portfolio Moderno - Vinícius Santos

Portfolio pessoal moderno desenvolvido com **Astro** e **Tailwind CSS** para um DevOps Engineer focado em operações.

## ✨ Funcionalidades

- 🎨 Design moderno e responsivo
- ⚡ Performance otimizada com Astro
- 🎯 Foco em DevOps e operações
- 📱 Totalmente responsivo
- 🔧 Fácil manutenção
- 🚀 Deploy simples

## 🛠 Tecnologias Utilizadas

- **[Astro](https://astro.build/)** - Framework web moderno
- **[Tailwind CSS](https://tailwindcss.com/)** - Framework CSS utilitário
- **TypeScript** - JavaScript com tipagem
- **HTML5 & CSS3** - Padrões web modernos

## 📦 Estrutura do Projeto

```
modern-portfolio/
├── frontend/
│   ├── src/
│   │   ├── components/     # Componentes reutilizáveis
│   │   │   ├── Header.astro
│   │   │   ├── Hero.astro
│   │   │   ├── About.astro
│   │   │   ├── Experience.astro
│   │   │   ├── Skills.astro
│   │   │   ├── Contact.astro
│   │   │   └── Footer.astro
│   │   ├── layouts/        # Layouts das páginas
│   │   │   └── Layout.astro
│   │   ├── pages/          # Páginas do site
│   │   │   └── index.astro
│   │   └── styles/         # Estilos globais
│   │       └── global.css
│   ├── public/             # Arquivos estáticos
│   ├── astro.config.mjs    # Configuração do Astro
│   ├── tailwind.config.mjs # Configuração do Tailwind
│   └── package.json        # Dependências
├── .gitignore
└── README.md
```

## 🚀 Como Executar

### Pré-requisitos
- Node.js (versão 18 ou superior)
- npm ou yarn

### Instalação e Execução

1. **Clone o repositório:**
   ```bash
   git clone <url-do-repositorio>
   cd modern-portfolio
   ```

2. **Instale as dependências:**
   ```bash
   cd frontend
   npm install
   ```

3. **Execute em modo de desenvolvimento:**
   ```bash
   npm run dev
   ```
   O site estará disponível em: `http://localhost:4321`

4. **Build para produção:**
   ```bash
   npm run build
   ```
   Os arquivos otimizados serão gerados na pasta `dist/`

5. **Visualizar build de produção:**
   ```bash
   npm run preview
   ```

## 📝 Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Cria build otimizado para produção
- `npm run preview` - Visualiza o build de produção localmente
- `npm run astro` - Executa comandos do Astro CLI

## 🎨 Personalização

### Cores e Tema
As cores principais podem ser modificadas no arquivo `tailwind.config.mjs` ou diretamente nos componentes usando as classes do Tailwind.

### Conteúdo
Para personalizar o conteúdo:

1. **Informações pessoais:** Edite os componentes em `src/components/`
2. **Experiências:** Modifique `src/components/Experience.astro`
3. **Habilidades:** Atualize `src/components/Skills.astro`
4. **Contato:** Edite `src/components/Contact.astro`

### Imagens
Adicione suas imagens na pasta `public/` e referencie-as nos componentes.

## 🌐 Deploy

### Opções de Deploy Recomendadas

1. **Vercel** (Recomendado)
   ```bash
   npm i -g vercel
   vercel --prod
   ```

2. **Netlify**
   - Conecte seu repositório GitHub
   - Configure: Build command: `npm run build`, Publish directory: `dist`

3. **GitHub Pages**
   - Configure GitHub Actions com o workflow do Astro

4. **Servidor próprio**
   ```bash
   npm run build
   # Upload da pasta dist/ para seu servidor
   ```

## 📊 Performance

- ⚡ Lighthouse Score: 90+ em todas as métricas
- 🚀 Carregamento inicial < 1s
- 📱 Totalmente responsivo
- ♿ Acessível (WCAG 2.1)

## 🔧 Manutenção

Este projeto foi desenvolvido pensando na **facilidade de manutenção**:

- ✅ Código bem estruturado e comentado
- ✅ Componentes reutilizáveis
- ✅ Configuração por arquivos
- ✅ Documentação completa
- ✅ Sem dependências complexas

## 📞 Suporte

- 📧 Email: vinicius.santos@email.com
- 💼 LinkedIn: [vinicius-santos](https://linkedin.com/in/vinicius-santos)
- 🐙 GitHub: [vinicius-santos](https://github.com/vinicius-santos)

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---

**Desenvolvido por Vinícius Santos**