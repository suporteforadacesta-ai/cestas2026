# Dinheiro no Lugar

Planner financeiro para quem faz cestas personalizadas. Separa o caixa do
negócio do caixa pessoal, calcula o preço certo de cada cesta e avisa
quando algo pede atenção (margem baixa, retirada maior que o lucro,
reserva fraca).

## Arquivo

Tudo está em `index.html` — um único arquivo HTML/CSS/JS, sem build e
sem dependências externas (as fontes vêm embutidas no próprio arquivo).

## Como abrir

Basta abrir `index.html` direto no navegador — não precisa de servidor.

## Como funciona

Os dados ficam guardados só no navegador de quem está usando
(`localStorage`), sem servidor e sem conta. Por isso a aba **Ajustes** tem
botões de backup (`.json`) e exportação (`.csv`) — use-os com regularidade,
porque limpar os dados do navegador ou trocar de aparelho apaga os
lançamentos se não houver backup.

## Publicar em outro lugar

Como é um arquivo único e estático, também dá para publicar em qualquer
hospedagem que sirva HTML puro (Netlify, GitHub Pages, Vercel). O arquivo
já se chama `index.html` de propósito — é o nome que essas hospedagens
esperam encontrar na raiz do projeto para servir como página inicial.
