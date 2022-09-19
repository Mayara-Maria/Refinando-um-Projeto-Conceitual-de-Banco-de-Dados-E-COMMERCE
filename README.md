# Refinamento de um Projeto Conceitual de Banco de Dados 
Desafio do Boootcamp Data Base Experience da DIO

***E-commerce***

**Narrativa:**

Produto

* Os produtos são vendidos por uma unica plataforma oline. Contudo, estes podem ter vendedores distintos (terceiros);
  
* Cada produto possui um fornecedor;
  
* Um ou mais produtos podem compor um pedido.
  

Cliente

* O cliente pode se cadastar no site com seu CPF ou CNPJ;
  
* O endereço do cliente irá determinar o valor do frete;
  
* Um cliene pode comprar mais de um pedido. Este tem um período de carência para devolução do produto.
  

Pedido

* Os pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega;
  
* Um produto ou mais compoem o pedido;
  
* O pedido pode ser cancelado.
  

**Objetivo:** Refinar o modelo apresentado acrescentando os seguintes pontos:

* Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter duas informações; 
  
* Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
  
*  Entrega – Possui status e código de rastreamento.
