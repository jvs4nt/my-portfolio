## Meu Portfolio — João Santos (jvs4nt)

Um portfolio moderno construído com React + Vite, Tailwind CSS e shadcn/ui.

**Principais Recursos**
- **UI moderna:** Tailwind CSS + shadcn/ui para componentes acessíveis e consistentes.
- **Carrosséis de projetos:** `embla-carousel-react` com navegação suave.
- **Rotas:** `react-router-dom` com páginas de Home e 404.
- **Feedbacks:** Toasts via `sonner` e `toaster`.
- **State/Data:** `@tanstack/react-query` para futuros dados reativos.

**Tecnologias**
- **Frontend:** React (SWC), Vite
- **Estilos:** Tailwind CSS, shadcn/ui
- **Carrossel:** embla-carousel-react
- **Roteamento:** react-router-dom
- **State/Data:** @tanstack/react-query

**Requisitos**
- Node.js 18+ (recomendado)
- Gerenciador de pacotes (npm, pnpm ou bun)

**Instalação**
Escolha seu gerenciador de pacotes e instale as dependências:

```bash
# usando npm
npm install

# usando pnpm
pnpm install

# usando bun
bun install
```

**Execução (Dev)**
Inicie o servidor Vite em modo desenvolvimento (porta configurada: 8080):

```bash
# npm
npm run dev

# pnpm
pnpm dev

# bun
bun run dev
```

Após iniciar, acesse: http://localhost:8080

**Build e Preview**
Gere os arquivos de produção e faça um preview local:

```bash
# build
npm run build

# preview (servidor estático do Vite)
npm run preview
```

**Scripts úteis**
- `dev`: inicia servidor de desenvolvimento
- `build`: build de produção
- `preview`: serve o build localmente

**Estrutura do Projeto**
- `index.html`: HTML base que injeta `src/main.tsx`
- `src/main.tsx`: bootstrap da aplicação com React e Vite
- `src/App.tsx`: providers globais (QueryClient, Tooltip, Router) e rotas
- `src/pages/Index.tsx`: página principal
- `src/pages/NotFound.tsx`: página 404
- `src/components/ProjectsCarousel.tsx`: carrosséis por categoria
- `src/components/ProjectCard.tsx`: cartão de projeto
- `src/components/ui/*`: componentes shadcn/ui
- `tailwind.config.ts`: configuração do Tailwind
- `vite.config.ts`: configuração do Vite e alias `@` → `src`

**Configurações**
- Alias de import: use `@` para importar de `src` (ex.: `@/components/...`).
- Porta Dev: 8080 (ajustável em `vite.config.ts`).

**Licença**
Projeto pessoal. Uso e inspiração permitidos; atribuição apreciada.

**Contato**
- Autor: João Santos — jvs4nt
- Projetos: confira a seção de carrosséis na Home.

