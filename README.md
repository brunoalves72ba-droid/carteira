# Carteira

Aplicativo de finanças pessoais em uma única página (HTML, CSS e JavaScript, sem dependências).

- Lançamentos únicos ou recorrentes (semanal a anual, com ou sem data de término)
- Orçamento por grupo de categorias
- Projeção anual editável, montada a partir das recorrências e da média dos gastos variáveis
- Simulador de compras parceladas

## Onde ficam os dados

Os lançamentos ficam no navegador de cada aparelho (localStorage). Este repositório público contém só o app, nunca os dados.

A sincronização entre aparelhos é opcional. Quando ativada, o app guarda um arquivo `dados.json` num repositório **privado** do próprio usuário, usando a API do GitHub com um token de acesso restrito a esse repositório (permissão Contents: leitura e escrita). O token fica salvo apenas no navegador de cada aparelho. Cada alteração vira uma versão no histórico do repositório privado.
