# 2POR1 · Link Bio

Página single-file para link de bio da 2POR1 Audiovisual.

## Estrutura

```
linkbio-2por1/
├── index.html        # página completa
├── favicon.svg       # ícone 2/1 gradiente
├── og-preview.jpg    # social preview (1200×630)
├── vercel.json       # config Vercel (cache + headers)
├── .gitignore
└── README.md
```

## Deploy no Vercel

### Opção 1 — Importar do GitHub (recomendado)

1. Acessar https://vercel.com/new
2. Importar o repositório `linkbio-2por1`
3. **Framework Preset:** Other
4. **Build Command:** (vazio)
5. **Output Directory:** (vazio — usa a raiz)
6. **Install Command:** (vazio)
7. Clicar em **Deploy**

Pronto. Cada push pro repo dispara um novo deploy automático.

### Opção 2 — Via CLI

```bash
npm i -g vercel
cd linkbio-2por1
vercel --prod
```

### Domínio personalizado

Settings → Domains → adicionar `2por1.com.br` (ou subdomínio).

## URL atual

- GitHub Pages: https://coltzgab.github.io/linkbio-2por1/
- Vercel: definir após primeiro deploy (ex: `2por1.vercel.app`)

## Personalizar

- **WhatsApp:** alterar `https://wa.me/5551998882224` no `index.html`
- **Tagline / Subtítulo:** dentro do bloco `.block-sub`
- **Cores:** variáveis CSS no `:root` do `<style>`
- **OG preview:** substituir `og-preview.jpg` (1200×630)

## Tech

- HTML/CSS puro, zero JS, zero dependências
- Fontes via Google Fonts CDN (Bebas Neue, Inter, Space Mono)
- SVG inline para o logo (escala sem perda)
- Glitch via pseudo-elementos + animação CSS
- Open Graph para preview no WhatsApp/Telegram/Discord
- Layout responsivo com breakpoints em 480px e 360px
