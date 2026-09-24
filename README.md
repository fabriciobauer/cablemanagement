# cablemanagement — catálogo de retalhos de cabos elétricos

Ferramenta que criei na Magnani Luz e Energia para controlar as **pontas de estoque de cabos** (os "retalhos" que sobram dos rolos): cada retalho é cadastrado com bitola, tamanho e cor/local na prateleira, e o balcão encontra na hora se existe uma sobra que atende o pedido do cliente, em vez de cortar um rolo novo.

> *A small single-page tool to catalog leftover electrical cable pieces (gauge, length, shelf) so the sales counter can quickly find a leftover that fits the customer's order.*

## Funcionalidades

- Cadastro de retalhos: bitola, tamanho e cor/prateleira
- Busca instantânea pela bitola
- Edição e exclusão de itens
- Dados salvos no próprio navegador (`localStorage`), sem servidor nem instalação

## Como usar

Basta abrir o `index.html` no navegador. Não há dependências nem build.

## Stack

HTML, CSS e JavaScript puro (sem frameworks).

## Contexto

Um dos meus primeiros projetos usados no dia a dia de uma empresa: resolve o controle das sobras de cabo com a solução mais simples possível — um arquivo só, que roda em qualquer computador do balcão.

## Autor

**Fabricio Bauer Chaves Junior** — [github.com/fabriciobauer](https://github.com/fabriciobauer)
