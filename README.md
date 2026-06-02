# AdventureWorks
An end-to-end Azure Data Engineering pipeline implementing a Medallion Architecture (Bronze/Silver/Gold) on the AdventureWorks dataset using Azure Data Factory, Databricks (PySpark), and Azure Synapse Analytics.

# 🧠 Data Integration and Processing Project
This project is designed to integrate and process data from various sources, including Git repositories and Azure Data Lake Storage Gen2. The project utilizes Azure Data Factory (ADF) pipelines to copy data from the Git repository to a raw storage location, and then performs data transformations using Apache Spark in the silver layer of a data warehousing architecture. The transformed data is then loaded into the gold layer, where it can be queried and analyzed using SQL views.

## 🚀 Features
* Data integration from Git repositories and Azure Data Lake Storage Gen2
* Data processing using Azure Data Factory (ADF) pipelines
* Data transformation using Apache Spark in the silver layer
* Data loading into the gold layer for querying and analysis
* SQL views for simplified data querying and analysis

## 🛠️ Tech Stack
* Azure Data Factory (ADF) for data integration and processing
* Azure Data Lake Storage Gen2 for data storage
* Apache Spark for data transformation in the silver layer
* Azure Synapse Analytics for data warehousing and SQL querying
* Azure Blob Storage for storing parquet files
* Python and Jupyter Notebooks for data transformation and processing
* JSON and SQL for data configuration and querying


## 📂 Project Structure
```
project
├── publish_config.json
├── dataset
│   └── datalake_ds.json
├── pipeline
│   ├── GitToRaw.json
│   ├── DynamicPipeline.json
│   └── ...
├── Transformations
│   └── Silver-Layer.ipynb
├── GoldLayer
│   └── sqlscript
│       └── Create Views Gold.json
├── factory
│   └── awp-project-meet.json
├── ...
└── README.md
```
