# Análise Exploratória de Dados (EDA) do Dataset AdventureWorks

## Introdução

Este repositório contém o código Python e um guia detalhado para a Análise Exploratória de Dados (EDA) do dataset AdventureWorks. O dataset, obtido do site da Microsoft, inclui informações sobre vendas de produtos eletrônicos.

## Objetivo

A EDA visa auxiliar na compreensão das características do dataset, na identificação de padrões e insights relevantes, e na preparação do terreno para análises e modelagens mais aprofundadas.

## Etapas da Análise

## Importação das Bibliotecas:

pandas para manipulação e análise de dados.
matplotlib e seaborn para visualização dos dados.

## Leitura do Dataset:

O dataset AdventureWorks.xlsx é carregado na variável df.
## Exploração Inicial do Dataset:

Verificação do formato e visualização das primeiras linhas para familiarização com as colunas e seus tipos de dados.

## Análise da Receita e do Custo:

Cálculo da receita total de vendas.
Cálculo do custo total dos produtos vendidos.
Cálculo do lucro total.

## Análise do Tempo de Envio:

Cálculo do tempo de envio para cada pedido (diferença entre data de venda e data de envio).
Verificação da ausência de valores nulos.
Criação de uma nova coluna 'dias_para_entrega' com a contagem de dias.
Renomeação da coluna 'dias_para_entrega' para 'Tempo de envio'.
Verificação do tipo de dados da coluna 'Tempo de envio'.
Análise da média de tempo de envio por marca.

## Análise do Lucro por Ano e Marca:

Agrupamento do lucro por ano e marca para identificar as marcas mais lucrativas em cada ano.

## Análise do Total de Produtos Vendidos:

Agrupamento da quantidade vendida por produto para identificar os produtos mais populares.
Visualização do total de produtos vendidos por produto em um gráfico de barras horizontal.

## Análise do Lucro Total por Ano:

Agrupamento do lucro por ano para visualizar a evolução do lucro ao longo do tempo.
Visualização do lucro total por ano em um gráfico de barras.

## Análise Detalhada das Vendas em 2009:

Criação de um novo dataframe df_vendas_2009 contendo apenas as vendas do ano de 2009.
Análise do lucro por mês em 2009.
Análise do lucro por marca em 2009.
Análise do lucro por classe de produto em 2009.

## Análise do Tempo de Envio:

Descrição estatística do tempo de envio.
Geração de um diagrama de boxplot para visualizar a distribuição do tempo de envio.
Geração de um histograma para visualizar a frequência de cada valor de tempo de envio.

## Identificação de Outliers:

Identificação de pedidos com tempo de envio excessivamente longo (20 dias).

## Salvamento do Dataset:

Salvamento do dataset df em um novo arquivo Excel edaAdventureWorks.xlsx para consulta futura.

## Considerações Finais

A EDA realizada fornece uma visão abrangente do dataset AdventureWorks, permitindo a identificação de tendências, padrões e insights relevantes para o negócio. As visualizações e análises estatísticas apresentadas neste repositório podem ser utilizadas como base para análises mais aprofundadas, como modelagem preditiva para prever vendas futuras ou análise de churn para identificar clientes com alto risco de inadimplência.

## Recomendações para Futuros Trabalhos

Explorar as características dos clientes, como região, demografia e histórico de compras, para identificar oportunidades de segmentação e personalização de marketing.
Analisar os fatores que influenciam o tempo de envio, como tipo de produto, destino da entrega e método de envio.
Implementar modelos de machine learning para prever o lucro futuro por produto, marca ou período de tempo.
Desenvolver dashboards interativos para facilitar a visualização e a análise dos dados.
