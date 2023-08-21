# Análise de Dados Utilizando Databricks

## Projeto
O objetivo principal deste Projeto consiste em conectar ao banco de dados da plataforma https://uibakery.io/sql-playground utilizando a base de dados do Ecommerce e realiza alguns tratamentos e análises sobre o mesmo utilizando Spark e Databricks. A versão do community é utilizada para esse fim.

## Arquivos
- Diagrama ER das tabelas em "diagrama_er.png"
- Notebook Databricks em "script_databricks.dbc" ou para abrir no Jupyter em "script_jupyter.ipynb"

## Objetivos que o projeto contempla
- Salva as tabelas no formato parquet
- Merge entre as tabelas do database (source) e os arquivos parquet, o merge contém a lógica de insert, update e delete.
- Análise sobre as seguintes perguntas:
  - Qual país possui a maior quantidade de itens cancelados?
  - Qual o faturamento da linha de produto mais vendido, considere como os itens Shipped, cujo o pedido foi realizado no ano de 2005?
  - Nome, sobrenome e e-mail dos vendedores do Japão, o local-part do e-mail deve estar mascarado.
