<div align="center">

# ▶️ VidFlow

**Plataforma de vídeos inspirada no YouTube, com busca e filtro por categoria.**

[![Site](https://img.shields.io/badge/Acessar_site-vid--flow--sigma.vercel.app-799EEB?style=for-the-badge&logo=googlechrome&logoColor=white)](https://vid-flow-sigma.vercel.app)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![json-server](https://img.shields.io/badge/json--server-000000?style=for-the-badge&logo=json&logoColor=white)

</div>

---

## Sobre

Projeto de estudo de front-end: uma página de vídeos no estilo do YouTube, com menu lateral,
inscrições, barra de categorias e grade de vídeos carregada de uma API.

## Visão Geral

O projeto permite:

- listar vídeos a partir de uma API (`backend/videos.json`)
- **pesquisar** vídeos pelo título
- **filtrar por categoria** (Front-end, Mobile, Data Science, Programação...)
- navegar num layout responsivo, montado com Flexbox

## Estrutura

```text
.
|-- index.html
|-- script.js            busca, pesquisa e filtro dos vídeos
|-- backend/videos.json  dados dos vídeos
`-- css/                 reset, flexbox e estilos
```

## Rodando Localmente

Os vídeos são buscados com `fetch`, então é preciso servir o JSON. Com o
[json-server](https://github.com/typicode/json-server):

```bash
npx json-server --watch backend/videos.json
```

E abra o `index.html` com uma extensão como o Live Server.
