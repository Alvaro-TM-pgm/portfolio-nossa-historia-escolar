# Nossa História — Portfólio Escolar

Portfólio escolar digital com trajetórias pessoais e registros de atividades coletivas de 2026.

## Tecnologias

HTML semântico, CSS responsivo e JavaScript sem dependências de build. O conteúdo fica separado em `content.json` para facilitar ajustes, e o projeto pode ser hospedado diretamente no GitHub Pages.

## Estrutura

- `index.html`: seções e navegação.
- `styles.css`: identidade visual, layout responsivo e acessibilidade de foco.
- `app.js`: renderização do conteúdo, navegação, carrosséis e lightbox.
- `content.json`: textos dos perfis e trabalhos.
- `assets/images/integrantes/`: fotos pessoais.
- `assets/images/trabalhos/`: fotos dos trabalhos.
- `favicon.svg`: ícone do site.

## Como substituir fotos

Adicione fotos reais nas pastas `assets/images/integrantes/dayane/`, `leticia/` e `thayna/`. Os cinco nomes do carrossel são `dayane-01.jpg` a `dayane-05.jpg` (e equivalentes para `leticia` e `thayna`). Para as atividades, use os nomes indicados no `app.js`, por exemplo `trabalho-1708-01.jpg` a `trabalho-1708-03.jpg`, `trabalho-0209-01.jpg` e os seis arquivos de mapas mentais `dayane-mapa-01.jpg` etc. Os espaços sem arquivo aparecem identificados para edição.

## Como editar informações

Edite `content.json` mantendo a estrutura JSON. Os textos estão organizados em `profiles` e `works`; mantenha perfis em ordem alfabética e trabalhos em ordem cronológica. Procure `EDITAR AQUI` em `app.js` para ajustar imagens e acrescente novas atividades depois do trabalho de 16 de setembro no `content.json` e no espaço de futuro trabalho em `app.js`.

## Publicação

O repositório está preparado para GitHub Pages com arquivos estáticos na raiz. No GitHub, abra **Settings → Pages**, escolha **Deploy from a branch**, selecione `main` e `/ (root)`, e salve. Para publicar alterações, faça commit e push para `main`.

URL GitHub Pages: https://alvaro-tm-pgm.github.io/portfolio-nossa-historia-escolar/

