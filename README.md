# Desafio ecommerce
Entrega do desafio curso da DIO

Projeto Conceitual - E-commerce
Visão Geral
Este projeto modela um sistema de e-commerce que gerencia clientes, fornecedores, produtos, pedidos, pagamentos e entregas. O objetivo é garantir um fluxo eficiente de compras online, permitindo múltiplas formas de pagamento, controle de estoque e rastreamento de entregas.

Entidades e Relacionamentos
Cliente

Pode ser Pessoa Física (PF) ou Pessoa Jurídica (PJ), mas nunca ambas.
Cada cliente pode realizar múltiplos pedidos.
O cliente pode cadastrar múltiplos cartões de crédito para facilitar pagamentos futuros.
Cartão de Crédito

Associado a um cliente específico.
Armazena os últimos 4 dígitos do cartão, nome do titular, bandeira e data de validade.
O cliente pode escolher um dos cartões cadastrados ao realizar um pagamento.
Fornecedor

Empresas que fornecem produtos ao e-commerce.
Cada fornecedor pode disponibilizar vários produtos.
Produto

Itens disponíveis para venda, podendo ser vendidos por fornecedores diretos ou terceiros.
Um produto pode estar associado a múltiplos vendedores.
Estoque

Controla a quantidade de produtos disponíveis e seus locais de armazenamento.
Pedido

Representa uma compra realizada por um cliente.
Pode conter múltiplos produtos e diferentes formas de pagamento.
Possui um status de entrega e um código de rastreamento para acompanhamento.
Pagamento

Permite múltiplas formas de pagamento para um mesmo pedido.
Pode estar associado a um cartão de crédito cadastrado pelo cliente ou a outras formas de pagamento, como Pix, Boleto ou Transferência.
Entrega

O status de entrega pode ser "Pendente", "Enviado", "Entregue" ou "Cancelado".
Cada pedido possui um código de rastreamento para acompanhamento da entrega.
Objetivo do Banco de Dados
Permitir que os clientes realizem pedidos e paguem com diferentes formas de pagamento, incluindo múltiplos cartões de crédito.
Garantir a rastreabilidade dos pedidos, desde a compra até a entrega.
Manter um controle eficiente de estoque e fornecedores.
Oferecer flexibilidade no gerenciamento de pagamentos, melhorando a experiência do cliente.
