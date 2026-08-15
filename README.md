# Adventure_Works_DataEngineering_Project
A production grade Modern Data Platform built on Microsoft Azure, designed to handle the complexities of high-velocity data.This solution implements a robust **Medallion Architecture**, transforming raw enterprise data into a strategic asset for business intelligence and data science initiatives.

A cloud native tech stack to ensure modularity, scalability and security:

**Data Ingestion & Orchestration**: Azure Data Factory (ADF) handles automated, parameter driven ELT pipelines, ensuring efficient data movement from external APIs to the Lakehouse.

**Medallion Data Lakehouse**:  
**Bronze**: Raw, immutable data ingestion.  
**Silver**: Curated, cleansed, and schema enforced data via Azure Databricks (Apache Spark).  
**Gold**: Optimised serving layer via Azure Synapse Analytics.

**Processing**: Distributed computation using PySpark to manage large scale data transformations and performance optimisation.

**Data Warehousing**: High performance analytical querying using Synapse Server less SQL Pools and external table definitions.

**BI & Analytics**: Seamless integration with Power BI for real-time visualisation and executive level reporting.

