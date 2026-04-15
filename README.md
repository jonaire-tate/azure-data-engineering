# Azure Data Engineering
Cloud data engineering coursework completed as part of the BU Master of Data Science program, using Microsoft Azure and Power BI to build data pipelines, query large datasets, and visualize results.

## Tools and Technologies

- Azure Data Factory
- Azure Synapse Analytics
- Azure Data Lake Storage Gen2
- Azure Cosmos DB
- Azure SQL Database
- Power BI

## Projects

### ETL Pipeline - Azure Data Factory
Built a two-step pipeline that ingests a zipped file from and HTTP source, copies it to Azure Blob Storage, and unzips it for downstream use. Pipeline executed successfully with both Copy Data activities completing in sequence.

### Large-Scale SQL Queries - Azure Synapse Analytics
Queried a Ford vehicle crash dataset (~1,045 parquet files) stored in ADLS Gen2. Wrote SQL to filter Ford F-150 crashes between 1990-2010, aggregate by year, and visualize results as bar and line charts.

### NoSQL Queries - Azure Cosmos DB
Queried a movies dataset using Cosmos DB SQL API. Wrote JOIN queries to filter films by production company and keyword (e.g., returning all files tagged with "artificial intelligence").

### Relational Database - Azure SQL Database
Designed and created a relational table schema for a consumer complaints dataset, including fields for compaint ID, product, issue, company response, and state.

### Data Visualization - Power BI
Connected Power BI to the Ford crash dataset and built a dashboard showing complaint counts by model and deaths by year.

## Screenshots

See the '/screenshots' folder for evidence of completed work in each tool.
