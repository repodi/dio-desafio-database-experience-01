# Desafio modelo conceitual Ecommerce
Desafio do bootcamp da DIO referente ao bootcamp Database Experience, que tem por objetivo a construção de um modelo conceitual de banco de dados referente a um Ecommerce. 

## Objetivo:

Refine o modelo apresentado acrescentando os seguintes pontos:

 - Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
 - Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
 - Entrega – Possui status e código de rastreio;

## Narrativa do escopo: 

### Produto
- Os produtos são vendidos por uma única plataforma online. Contudo estes podem ter vendedores distintos (terceiros); 
- Cada produto possui um fornecedor;
- Um ou mais produtos podem compor o pedido; 

### Cliente
 - O cliente pode se cadastrar no site com o CPF ou CNPJ;
 - O endereço do cliente irá determinar o valor do frete; 
 - Um cliente pode comprar mais de um pedido. Este tem um período de carência para a devolução do produto; 

 ### Pedido 
 - Os pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega;
 - Um produto ou mais compoem o pedido;
 - O pedido pode ser cancelado;