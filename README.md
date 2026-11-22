# Rute, a Capivara Cristã — site estático

Versão estática (HTML + CSS + JS, sem etapa de build) do protótipo do site. Não é o projeto Astro da especificação.

## Publicar no GitHub Pages
1. Envie o conteúdo desta pasta para a raiz do repositório.
2. Em Settings → Pages, escolha "Deploy from a branch", branch `main`, pasta `/ (root)`.
3. Os caminhos são relativos: funciona em usuario.github.io/repositorio e em domínio próprio.

## Estrutura
- `index.html`: página inicial e demais páginas (navegação por #hash)
- `favicon.svg`: laço rosa (#F29999)
- `assets/css/style.css`: estilos e paleta oficial (variáveis no topo)
- `assets/js/main.js`: conteúdo e navegação
- `assets/img/rute.webp`: recorte da ilustração da Rute enviada
- `assets/downloads/`: pasta para os PDFs gratuitos
- `robots.txt`, `.nojekyll`

## Editar o conteúdo (assets/js/main.js)
- Redes oficiais: `yt`, `ig`, `tk`
- Vídeos: lista `V` (ID do YouTube + título)
- Histórias de exemplo: `S` · Jogos: `G` · Textos das demais páginas: `P`

## Pendências
- Histórias, jogos e downloads reais (hoje são exemplos ou estados vazios)
- Versículo em destaque (definir a tradução)
- Meios de contribuição (PIX/links) e textos jurídicos revisados
- Imagem de compartilhamento (og:image), sitemap e fontes hospedadas localmente (hoje vêm do Google Fonts)
