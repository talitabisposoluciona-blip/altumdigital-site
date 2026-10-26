# altumdigital.com.br

Site estático da Altum Digital (landing page + blog), hospedado no Netlify com deploy automático a partir deste repositório.

## Estrutura
- `index.html` — landing page
- `blog.html` — índice do blog
- `blog/*.html` — artigos (a URL pública é o slug sem `.html`, ex.: `/blog/api-oficial-whatsapp`)
- `sitemap.xml` — todas as URLs indexáveis
- `robots.txt`

## Como publicar uma alteração
Qualquer commit na branch `main` gera um deploy automático no Netlify em ~1 minuto. Nunca mais é preciso arrastar arquivos manualmente.

## Ao criar um artigo novo
1. Salvar o HTML em `blog/<slug>.html`
2. Adicionar o card em `blog.html`
3. Adicionar a URL em `sitemap.xml`
4. Commit → deploy automático → pedir indexação no Search Console
