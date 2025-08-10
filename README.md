# CloudDataPipeline
A full end-to-end data engineering workflow implemented on Azure, showcasing:

- **Data Ingestion & Orchestration** with Azure Data Factory (ADF)  
- **Data Processing & Transformation** using Azure Databricks and PySpark  
- **Data Storage** on Azure Data Lake Storage Gen2 (ADLS Gen2)

## Tech Stack
- **Microsoft Azure**
- **Azure Data Lake Storage Gen2 (ADLS Gen2)**
- **Azure Data Factory (ADF)**
- **Azure Databricks**
- **Python(PySpark)**

## Pipeline Workflow
1. **Ingested** raw data from source to **ADLS Gen2** using **ADF**.
2. **Transformed** data in **Azure Databricks** using **PySpark**.
3. **Stored** processed data back in **ADLS Gen2**.
