# NYC-TAXI-DataEngineering-PROJECT

## Overview

This project provides a comprehensive end-to-end data engineering solution using Azure cloud services, encompassing the design and implementation of data workflows from scratch.
Focusing on real-time data ingestion, transformation, and processing, the project leverages key Azure tools such as Azure Data Factory, Azure Databricks, and Delta Table to build scalable and efficient data pipelines and analytics solutions.
Created a end-to-end solutions and connected DataBricks Delta table to Power BI for visualization.


## Data Architechture
![WhatsApp Image 2025-05-21 at 16 37 20_7de57877](https://github.com/user-attachments/assets/fae1727e-15c2-4d84-b2a4-1a8fb406a3b0)



## Technology Used
1. Programming Language - Python 
2. Scripting Language - SQL 
3. Azure Cloud
   - Azure Data Factory
   - Azure Data lake
   - Azure Databricks
   - Delta Table
  
     
## Step 1. Environment Setup

Azure Account Creation: Started by creating an Azure account and configuring the necessary resource groups.  <br>
Service Provisioning: Deployed key services such as Azure Data Factory, Azure Data Lake Storage, Azure Databricks, and Power BI.


## Step 2. Data Ingestion

Sources: I worked with multiple sources. This included local CSV files, as well as external APIs using HTTP services. I used Azure Data Factory to automate the ingestion process—connecting to APIs via HTTP connectors and importing local files into Azure Data Lake Storage.  <br>
Azure Data Factory: Used as a managed ETL (Extract, Transform, Load) service to automate data ingestion, orchestrate workflows, and move data into cloud storage.


## Step 3. Data Storage

Azure Data Lake Storage: Chosen for scalable, secure, and cost-effective storage of raw and processed data.    <br>
Data Organization: Structured storage with folders for raw, staging, and processed data to maintain an organized pipeline.


## Step 4. Data Processing & Transformation

Azure Databricks: Utilized for data processing via Spark clusters.      <br>
Transformations: Performed data cleaning, filtering, aggregation, and transformations using PySpark notebooks.      <br>
Delta Lake: Implemented for enhanced data management with features like ACID transactions, versioning, and time travel.      <br>


## Step 5. Building Data Pipelines

Orchestration: Managed dependencies between tasks, ensuring proper sequencing and monitoring.      <br>
Demonstrated how to handle end-to-end data workflows, from raw data collection to actionable insights.


## Step 6. Data Visualization & Reporting
Power BI Integration: Connected processed data from Delta Lake or Azure SQL Database to Power BI.      <br>
Dashboard Development: Built interactive dashboards for data insights, enabling stakeholders to explore data visually.      <br>



     
## Dataset used
Original data source: https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
