# Azure-Olympic-Insights- ETL Pipeline

## Project Overview

This project, titled "Azure Olympic Insights" is designed to demonstrate the use of various Azure services in a data engineering pipeline, focusing on the 2021 Tokyo Olympics dataset from Kaggle. The project involves data ingestion, transformation, and analysis, showcasing skills in Azure Data Factory, Data Lake Gen 2, Databricks, and Synapse Analytics. Additionally, we will explore data visualization using Power BI / Tableau.

## Tools and Technologies

- **Azure Data Factory**: For creating data ingestion pipelines.
- **Azure Data Lake Gen 2**: For storing raw and processed data.
- **Azure Databricks**: For data transformation and cleaning.
- **Azure Synapse Analytics**: For data analysis and querying.
- **Power BI / Tableau**: For data visualization and dashboard creation.

## Project Workflow

1. **Data Ingestion**:
   - Source: Kaggle (2021 Tokyo Olympics dataset)
   - Tool: Azure Data Factory
   - Process: Download raw data from Kaggle and ingest it into Azure Data Lake Gen 2.

2. **Data Transformation**:
   - Tool: Azure Databricks
   - Process: Perform data cleaning and transformation, including removing duplicates and dropping unnecessary columns. The transformed data is then uploaded back to Azure Data Lake Gen 2.

3. **Data Analysis**:
   - Tool: Azure Synapse Analytics
   - Process: Analyze the transformed data using SQL queries to extract meaningful insights.

4. **Data Visualization** (optional):
   - Tools: Power BI / Tableau
   - Process: Create interactive dashboards to visualize the insights derived from the data analysis.
