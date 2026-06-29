# Ranking da Comida

Mini-app particular para David & Bruna criarem rankings de comida por categoria.

## O que já tem

- Cadastro de categorias: hambúrguer, batata, pizza, sobremesa etc.
- Cadastro de avaliação por comida/lugar.
- Campo de consumo: **No local** ou **Delivery/retirada**.
- Quando for delivery, a avaliação de **local/ambiente** some automaticamente.
- Notas de sabor, preço/benefício, atendimento, apresentação, porção e local.
- Cálculo automático da nota final.
- Ranking geral e por categoria.
- Pesquisa por comida, lugar ou cidade.
- Editar e excluir avaliações.
- Gerar texto do ranking para WhatsApp.
- Backup em JSON para baixar/importar depois.

## Importante sobre salvamento

Esta primeira versão salva os dados no próprio navegador usando `localStorage`.

Isso significa:

- Se abrir no mesmo celular/navegador, as informações continuam salvas.
- Se trocar de celular, limpar navegador ou abrir em outro aparelho, os dados não aparecem automaticamente.
- Para salvar em nuvem de verdade entre aparelhos, o app precisa ser conectado a um banco externo, como Supabase ou Firebase.

## Link esperado pelo GitHub Pages

Depois de ativar o GitHub Pages no repositório, o link deverá ficar assim:

`https://davidruans.github.io/ranking-comida/`
