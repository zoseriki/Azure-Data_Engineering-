# Store Analytics Pipeline

This project demonstrates an end-to-end data engineering solution using Azure:

- **Azure Data Factory (ADF)** → Ingestion (Bronze layer)
- **Azure Databricks (PySpark/SQL)** → Transformation & Aggregation (Silver & Gold)
- **Azure Data Lake Storage (ADLS)** → Data Lakehouse storage
- **Power BI** → Visualization

## Repo Structure
- `adf/` → ADF pipelines (JSON)
- `databricks/` → Notebooks (.py/.dbc)
- `powerbi/` → Dashboards (.pbix)
- `docs/` → Documentation

## Architecture
Bronze → Silver → Gold Medallion Architecture
