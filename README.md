# HelpDesk — Frontend

Interface web do sistema HelpDesk. Site estático em HTML, CSS e JavaScript puros, hospedado no GitHub Pages.

Este repositório contém **apenas a camada de apresentação**. O código do backend (FastAPI), modelos de dados e lógica de negócio ficam em um repositório separado.

## Configuração

Antes do deploy, ajuste o endpoint da API em `config.js`:

```js
window.API_URL = "https://sua-api.exemplo.com";
```

## Execução local

```bash
python -m http.server 5500
```

Acessível em `http://localhost:5500`. Para uso local, aponte `config.js` para o backend rodando em `http://localhost:8000`.

## Estrutura

```
.
├── index.html      # Estrutura da UI
├── styles.css      # Estilos
├── config.js       # URL da API
└── app.js          # Lógica e chamadas HTTP
```

## Deploy

Hospedado via GitHub Pages a partir da branch `main`. Cada push republica o site automaticamente.

## Autora

Emilly Yorke
