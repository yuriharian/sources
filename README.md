# sources

Imagens públicas (favicons e logos) usadas pelos projetos. Uma pasta por projeto:

- `talon/images/`: ícones do Talon (favicon, apple-touch-icon, android-chrome, webmanifest).
- `nova/images/`: favicon e logo do Nova.
- `images/`: cópia antiga (caminho original do Talon). Mantida até o Talon em produção usar `talon/images/`; depois pode ser removida.

Uso no Apps Script: `HtmlOutput.setFaviconUrl('https://raw.githubusercontent.com/yuriharian/sources/refs/heads/main/<projeto>/images/<arquivo>')`.
O repositório é público só por isso: só entram aqui arquivos que podem ser vistos por qualquer pessoa.
