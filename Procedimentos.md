# Desenvolvimento do Painel Gerencial no Power BI

Este documento detalha as etapas envolvidas no desenvolvimento do painel gerencial no Power BI, baseado nas especificações e requisitos fornecidos.

## Configuração Inicial

Antes de iniciar o desenvolvimento do painel, foram realizados os seguintes passos iniciais:
- **Importação das Bases de Dados**: As bases de dados foram importadas para o Power BI.
- **Configuração das Colunas**: As colunas foram configuradas conforme as especificações determinadas para garantir a integridade e a relevância dos dados.

## Etapa 01: Cartões

**Objetivo**: Fornecer uma visão geral rápida e impactante dos principais indicadores de desempenho.

### Análise das Tabelas

As tabelas **BASE DE COMPRAS** e **BASE DE CLIENTES** foram analisadas para identificar as colunas e valores relevantes.

### Criação dos Cartões

Os cartões foram configurados para apresentar os seguintes indicadores:

1. **Quantidade Total de Vendas**:
   - Mostra o total de vendas no período selecionado. O uso de um filtro de datas permite visualizar o desempenho em diferentes intervalos de tempo.

2. **Valor Total de Vendas Sem Frete**:
   - Exibe o valor total das vendas, excluindo o custo de frete, para avaliar a receita gerada pelos produtos.

3. **Valor Total de Vendas Com Frete**:
   - Mostra o valor total das vendas incluindo o frete, refletindo o impacto dos custos adicionais sobre o valor final de venda.

4. **Quantidade de Clientes**:
   - Apresenta o número total de clientes registrados, fornecendo uma visão sobre a base de clientes.

5. **Média de Renda dos Clientes**:
   - Calcula e exibe a renda média dos clientes, permitindo uma análise do perfil econômico da base de clientes.

## Etapa 02: Gráficos de Linhas

**Objetivo**: Visualizar tendências e padrões ao longo do tempo.

1. **Contagem de Vendas por Mês**:
   - Exibe o número total de vendas agrupadas por mês, permitindo identificar variações e tendências mensais.

2. **Valor Total de Vendas por Mês**:
   - Mostra o valor total das vendas por mês, oferecendo uma perspectiva clara da receita mensal.

## Etapa 03: Gráficos de Barras

**Objetivo**: Comparar diferentes categorias e distribuições.

1. **Quantidade de Vendas por Categoria**:
   - Apresenta a quantidade de vendas para cada categoria de produto, facilitando a análise de desempenho por categoria.

2. **Valor Total de Vendas por Categoria**:
   - Mostra o valor total das vendas para cada categoria, permitindo a comparação de receita gerada por diferentes categorias.

3. **Distribuição de Idades dos Clientes**:
   - Exibe a faixa etária dos clientes, ajudando a entender a demografia da base de clientes.

4. **Distribuição de Renda dos Clientes**:
   - Apresenta a faixa de renda dos clientes, fornecendo insights sobre o perfil econômico dos consumidores.

## Etapa 04: Filtros

**Objetivo**: Permitir a personalização e segmentação dos dados conforme as necessidades do usuário.

1. **Filtros Interativos**: Foram adicionados filtros para que os usuários possam personalizar a visualização dos dados de acordo com diferentes dimensões:
   - **Bandeira**: Filtra os dados por bandeira de cartão de crédito ou outras categorizações relevantes.
   - **Estado**: Permite selecionar e visualizar dados por estado geográfico.
   - **Canal de Venda**: Filtra por canal de venda (ex. online, loja física).
   - **Departamento**: Permite a análise por departamento específico dentro da organização.
   - **Idade**: Filtra os dados com base na faixa etária dos clientes.
   - **Faixa de Renda**: Permite visualizar dados de acordo com a faixa de renda dos clientes.
   - **Estado**: Filtra os dados com base no estado onde os clientes nasceram.

