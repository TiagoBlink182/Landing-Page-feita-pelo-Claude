# Vinho do Gringo — Landing Page

Landing page de consultoria de vinhos do Tiago (Vinho do Gringo), pronta para publicar no **GitHub Pages**.

## Estrutura
```
vinhodogringo/
├── index.html        → página principal
├── css/style.css      → estilos (cores da marca, tipografia, animações)
├── js/main.js         → menu mobile, animações de rolagem, FAQ
├── assets/logo.png    → sua logomarca (usada como favicon, ícone e nas seções)
├── robots.txt         → indexação para buscadores
└── sitemap.xml        → mapa do site para SEO
```

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (ex: `vinho-do-gringo`).
2. Envie **todos os arquivos desta pasta** para a raiz do repositório (não dentro de uma subpasta).
3. No GitHub, vá em **Settings → Pages**.
4. Em "Branch", selecione `main` e a pasta `/ (root)`. Clique em **Save**.
5. Em alguns minutos sua página estará no ar em:
   `https://SEU-USUARIO.github.io/vinho-do-gringo/`

## Antes de publicar, ajuste

- Em `robots.txt` e `sitemap.xml`, troque `SEU-USUARIO` e `SEU-REPOSITORIO` pela URL real do seu GitHub Pages.
- Em `index.html`, as tags `<meta property="og:url">` e `<link rel="canonical">` usam `./` (caminho relativo) — funcionam automaticamente, mas você pode trocar pela URL completa depois de publicar.
- Para trocar o número de WhatsApp ou o @ do Instagram, use "localizar e substituir" no `index.html`:
  - WhatsApp: `5551993416111`
  - Instagram: `vinhodogringo`

## O que já está pronto
- Cores e tipografia baseadas na sua logomarca (vinho tinto, dourado e creme).
- Botão flutuante de WhatsApp + mais 3 chamadas para ação com o mesmo link.
- Links para o Instagram em 4 pontos da página, com hover de elevação + sombra vinho (igual ao botão do WhatsApp).
- Seção "Quem sou", "Consultoria", "Como funciona", "Entrega" (Parobé x Brasil todo), FAQ e Contato com mapa.
- SEO técnico: título, meta description, Open Graph, Twitter Card, dados estruturados (Schema.org `LiquorStore` + `FAQPage`).
- Acessibilidade: navegação por teclado, textos alternativos em imagens, `prefers-reduced-motion` respeitado.
- Totalmente responsiva (celular, tablet e desktop).
