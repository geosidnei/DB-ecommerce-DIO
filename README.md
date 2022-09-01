# DB-ecommerce-DIO
Modelo de E-Commerce

Entidades Principais:

- Clientes cadastrados (Cliente)
- Vendedores do site (Terceiro) [a proprietária do site está incluída aqui]
- Produtos a venda (Produto)
- Pedidos do cliente (Pedido)
- Fornecedores de produtos (Fornecedor)
- Locais de estoque dos produtos (Estoque)

** Entidades de tipo

- Forma de Pagamento (FormaPagamento)
- Tipo de status (StatusTipo)
- Categoria do produto (CategoriaProduto)

** Entidades relacionadas

- Forma de pagamento do cliente (FormaPagamentoCliente)
- Produtos que o terceiro oferece (TerceiroProduto)
- Pedididos com os produtos do cliente (PedidoTerceiroProduto)
- Status da entrega dos produtos do pedido (PedidoTerceiroProdutoStatus)
- Status do pedido (StatusPedido)
- Produtos em estoque (ProdutoEstoque)
- Produtos que o fornecedor dispõem (FornecedorProduto)

** Contexto:

- O Cliente pode ter mais de uma forma de pagamento;
- O cliente pode ter mais de um pedido;
- Inserir a informação de data prevista de entrega do produto;
- O cliente pode verificar o preço do produto;
- O cliente pode verificar o status do pedido e da entrega a qualquer momento;
- Terceiros podem utilizar o site para realizar venda;
- Inserir a indicação de quem vende e entrega o produto;
- Inserir indicação de produto disponível.
