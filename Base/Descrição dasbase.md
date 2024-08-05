# Repositório de Dados de Compras e Clientes

Este repositório contém informações sobre compras e clientes. Os dados estão organizados em tabelas que armazenam detalhes sobre cada transação e sobre os clientes que realizaram as compras.

## Estrutura da Base de Dados

### Tabelas

#### 1. Tabela: BASE DE COMPRA
Esta tabela contém informações detalhadas sobre cada compra realizada.

- **idcompra**: Número de identificação da compra.
- **idcanalvenda**: Canal de venda onde a compra foi realizada (por exemplo, online, loja física, etc.).
- **bandeira**: Bandeira do cartão utilizado para a compra.
- **Data**: Data da compra (formato: YYYY-MM-DD).
- **Preço**: Preço do produto na compra (excluindo frete).
- **Preço_com_frete**: Preço total da compra, incluindo o frete.
- **Nome_Departamento**: Nome do departamento ao qual o produto pertence.
- **estado**: Estado onde a compra foi realizada.
- **cliente_Log**: Identificação do cliente que realizou a compra.

#### 2. Tabela: BASE DE VENDAS
Esta tabela contém informações sobre os clientes.

- **cliente_Log**: Identificação do cliente (deve corresponder ao cliente_Log na tabela base_compra).
- **Idade**: Idade do cliente.
- **uf_nascimento**: Estado de nascimento do cliente.
- **Renda**: Renda do cliente.

## Relacionamentos Entre Tabelas

- **base_compra.cliente_Log** é uma chave estrangeira que se relaciona com **base_cliente.cliente_Log**.
