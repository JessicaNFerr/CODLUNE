Este pacote contém:
- `index.html`: versão original usando placeholders externos (placehold.co).
- `index-local.html`: versão que usa assets locais (pasta `assets/`).

## Como usar
1. Abra `index-local.html` no navegador para ver tudo com imagens locais.
2. Substitua as imagens em `assets/` pelas suas definitivas (mantenha os nomes, se quiser evitar trocar no HTML).
3. Ajuste os textos, links e WhatsApp diretamente no HTML.
4. (Opcional) Hospede em Vercel, Netlify ou S3/CloudFront. É 100% estático.

## Observações
- O site usa Tailwind via CDN. Caso leve para produção com build, recomendo extrair para um pipeline de build (PostCSS/Tailwind CLI) para reduzir CSS.
