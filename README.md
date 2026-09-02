# Meus Objetivos do Ano

Página simples feita durante o curso de HTML da Alura. A ideia era treinar HTML, CSS e JavaScript puro construindo algo com utilidade real: um painel com abas para quatro metas pessoais, cada uma com um contador regressivo até a data limite.

## O que tem aqui

- Abas clicáveis para alternar entre os objetivos (`main.js` cuida da troca de classes `ativo`)
- Contagem regressiva em dias, horas, minutos e segundos, atualizada a cada segundo
- Layout e estilos em `style.css`, sem frameworks

## Como rodar

Não tem build nem dependências. Basta abrir o `index.html` no navegador, ou servir a pasta com qualquer servidor estático (por exemplo `npx serve .`).

## Ajustando as datas

As datas de cada objetivo estão fixas em `main.js`, nas constantes `tempoObjetivo1` a `tempoObjetivo4`. Para reaproveitar o projeto com metas próprias, basta trocar esses valores.
