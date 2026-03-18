# Aluraflix

Essa API foi desenvolvida durante o [#alurachallengeback](https://www.alura.com.br/challenges/back-end) no período de 19 de Julho a 13 de Agosto.

No desafio, foi proposto o desenvolvimento de uma API para cadastro de videos, do zero. A escolha de stack do desafio era livre, e escolhi utilizar o Spring.

A API ainda possui melhorias a serem feitas, uma demosntração já esteve disponivel no Heroku, porém foi desativada após o fim do free tier.

## Endpoints disponíveis
Uma documentação mais completa será adicionada em breve, mas para testes simples, é possivel utilizar os endpoints listados abaixo.

- GET /videos
> Lista todos os videos atualmente cadastrados.

- GET /videos/{id}
> Lista detalhes do video com com o ID escolhido.

- POST /videos
> Cadastra um video, desde que as informações fornecidas sejam válidas.

- PUT /videos/{id}
> Atualiza informações do video cadastrado como ID escolhido.

- DEL /videos/{id}
> Deleta o video com o ID escolhido.

- GET /categorias
> Lista todas as categorias cadastradas atualmente.

- GET /categorias/{id}
> Lista detalhes da categoria com o ID escolhido.

- GET /categorias/{id}/videos
> Lista todos os videos cadastrados cuja categoria possui o ID escolhido.

- POST /categorias
> Cadastra uma nova categoria.

- PUT /categorias/{id}
> Atualiza informações da categoria como ID escolhido.

- DEL /cageorias/{id}
> Deleta a categoria com o ID escolhido.

