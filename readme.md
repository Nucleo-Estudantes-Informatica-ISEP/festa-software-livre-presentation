# 👋 Apresentação Festa Software Livre 2023 - Aveiro 👋

## Introdução 🔎

Este repositório contém a apresentação usada pelo NEI na Festa do Software Livre 2023, em Aveiro.

A apresentação usa uma ferramenta chamada [Marp](https://marp.app/) que permite escrever apresentações utilizando Markdown.

## Como usar ⚒️

Para editar a apresentação, basta editar o ficheiro `apresentacao.md` e abrir o ficheiro `apresentacao.html` no browser para ver o resultado.

`python -m http.server` pode ser usado para servir o ficheiro html localmente.

## Comando úteis 🤝

Para "compilar" a apresentação para html de forma a poder visualizá-la no browser, pode-se usar o seguinte comando:

```bash
npx @marp-team/marp-cli@latest -w presentation.md
```

Para exportar para pdf pode-se usar o seguinte comando:

```bash
npx @marp-team/marp-cli@latest --pdf presentation.md --allow-local-files
```
