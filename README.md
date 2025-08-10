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
1. **Ingested** raw data from source to **Bronze Layer** in **ADLS Gen2** using **ADF**.
2. **Transformed & cleaned** data in **Azure Databricks** (PySpark) into **Silver Layer**.
3. **Aggregated & optimized** data into **Gold Layer** for analytics and reporting.
4. Used **Delta Lake** for versioning, schema enforcement, and time travel.
5. **Unity Catalog** for governance.
