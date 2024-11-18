# 🚀 Projeto Northwind Pipeline - Azure Data Integration  

Este repositório contém as informações e a documentação do projeto realizado como parte de um estudo aprofundado de **Integração de Dados** utilizando ferramentas do ecossistema Microsoft Azure. O objetivo foi criar um pipeline de dados eficiente que integra **Azure Data Lake**, **Synapse Analytics**, e **Power BI**, utilizando os dados fictícios do banco de dados **Northwind** como base.  

## 🛠️ Ferramentas e Tecnologias Utilizadas  

### Armazenamento e Processamento de Dados  
- **[Azure Data Lake](https://azure.microsoft.com/pt-br/products/storage/data-lake):** Utilizado para armazenar os arquivos no formato **Parquet**, organizados em diferentes camadas (raw, processed e final).  
- **[Azure Synapse Analytics](https://azure.microsoft.com/pt-br/products/synapse-analytics/):** Ferramenta central para integração e análise de dados. Configurado tabelas externas e criado um modelo dimensional (esquema estrela) com tabelas fato e dimensões.  

### ETL e Orquestração  
- **[Azure Data Factory](https://azure.microsoft.com/pt-br/products/data-factory):** Utilizado para criar pipelines de ingestão e transformação de dados entre os diferentes serviços.  
- **[Databricks](https://www.databricks.com/):** Usado para pré-processamento e transformação de dados. Desenvolvido scripts em **PySpark** para limpeza, tratamento e carregamento dos dados no Data Lake.  

### Visualização de Dados  
- **[Power BI](https://powerbi.microsoft.com/):** Criação dashboards interativos para visualizar insights com base nas tabelas do modelo dimensional.  

### Desenvolvimento e Controle de Versão  
- **[Python](https://www.python.org/):** Utilizado para manipulação e transformação dos dados no Databricks.  
- **[GitHub](https://github.com/):** Gerenciamos o controle de versão e hospedagem dos scripts e notebooks do projeto.  
- **[Git](https://git-scm.com/):** Ferramenta usada para versionamento e colaboração no desenvolvimento.  

### Banco de Dados  
- **[SQL Pools - Synapse](https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/):** Criado tabelas e consultas SQL para modelagem e análise de dados.  


## 🌟 Estrutura do Projeto  

1. **Azure Data Lake**:  
   - Camadas definidas: **Raw**, **Processed** e **Final**.  
   - Dados armazenados no formato Parquet, otimizados para processamento.  

2. **Azure Synapse Analytics**:  
   - Criação de tabelas externas vinculadas ao Data Lake.  
   - Modelo dimensional utilizando o **esquema estrela**:  
     - **Tabela Fato:** Fato_Vendas.  
     - **Tabelas Dimensão:** Dim_Customers, Dim_Products, Dim_Employees, Dim_Shippers, entre outras.  

3. **Power BI**:  
   - Dashboard interativo mostrando insights sobre vendas, produtos mais vendidos, desempenho de funcionários e mais.  

---

## 📊 Resultados e Análises  

Os dashboards desenvolvidos permitiram identificar:  
- Produtos mais vendidos.  
- Regiões com maior volume de vendas.  
- Desempenho individual dos funcionários.  

### Link para o Dashboard  
[Northwind Dashboard]()  

---

## 👥 Equipe  

- **Francisco Taveira** - [GitHub](https://github.com/ftaveira-dev)  

---

## 📝 Considerações Finais  

Este projeto proporcionou uma oportunidade prática de explorar o ecossistema Microsoft Azure, aprimorar habilidades em manipulação e análise de dados, e desenvolver dashboards interativos para suporte a decisões. Alem de um contato inicial com o Synapse Analytics. 

