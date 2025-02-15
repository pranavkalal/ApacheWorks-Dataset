Azure Data Engineering Project: AdventureWorks Pipeline
Overview

This project implements an end-to-end Data Engineering pipeline on Azure Cloud using Azure Data Factory, Databricks, Synapse Analytics, and Power BI.

 Tech Stack

Cloud: Microsoft Azure
Storage: Azure Blob Storage (Bronze, Silver)
ETL: Azure Data Factory (Dynamic Pipelines, API Ingestion)
Processing: Databricks (PySpark)
Querying: Azure Synapse Analytics (Parquet Queries)
Visualization: Power BI

###Key Features

 Dynamic Data Ingestion: Extracting multiple datasets from GitHub via API into Azure Blob Storage (Bronze).
 Transformation with Databricks: Using PySpark to clean and transform data, then storing it in Silver.
 Querying with Azure Synapse: Running SQL queries on the transformed Parquet files.
Power BI Dashboard: Connecting the final dataset to Power BI for visualization.

 
 How to Use

1️⃣ Clone the repo

git clone https://github.com/your-username/Azure-Data-Engineering-Project.git

2️⃣ Setup Databricks & Azure Data Factory
3️⃣ Run the data pipeline scripts
4️⃣ Use Power BI for visualization
