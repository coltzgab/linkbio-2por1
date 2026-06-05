# 2POR1 · Link Bio

Página única auto-contida para link de bio do Instagram da 2POR1 Audiovisual.

## Preview

Abra `index.html` direto no navegador.

## Estrutura

```
linkbio-2por1/
├── index.html   # página completa, single-file
└── README.md
```

## Como subir no GitHub Pages

1. Criar repositório `linkbio-2por1` (público) na conta do GitHub
2. Push do conteúdo desta pasta para o repositório:
   ```bash
   cd linkbio-2por1
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/SEU_USUARIO/linkbio-2por1.git
   git push -u origin main
   ```
3. No GitHub → Settings → Pages → Source: `main` / root
4. Após ~1 minuto, a URL fica disponível em:
   `https://SEU_USUARIO.github.io/linkbio-2por1/`

## Personalizar

- **WhatsApp**: alterar `https://wa.me/5551998882224` no `index.html`
- **Tagline / Subtítulo**: blocos de texto dentro de `<a class="block">`
- **Cores**: variáveis CSS no `:root` do `<style>`

## Tecnologias

- HTML/CSS puro, sem dependências
- Fontes via Google Fonts (Bebas Neue, Inter, Space Mono)
- Logo 2POR1 inline como SVG vetorial com gradiente
- Efeito glitch via CSS pseudo-elementos + animação
