# Azure Data Factory and Databricks End-to-End Project - Medallion Architecture

Welcome to my Azure Data Analytics project, where I leverage Azure services to analyze trip transactions/ride-based data from a SQL server. This project is aimed at providing valuable insights by implementing the Medallion Architecture, a data structuring framework consisting of three layers: Bronze, Silver, and Gold. Each layer has its unique purpose, making data processing more efficient and insightful.

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [Project Goals](#projectgoals)
* [Tech Stack](#tech-stack)
* [Architecture Diagram](#architecture-diagram)
* [Dataset Used](#datasetused)
* [Project Codes and Files](#projectfiles)
* [Fact Dimension Tables - Data Modelling](#datamodelling)
* [Data Analysis and Visualisation](#datavisuals)
* [Contact](#contact)

<!-- Project Goals -->
## Project Goals<a name="projectgoals"></a>

The primary goal of this GitHub portfolio project is to implement robust analytics and insights on trip transactions data from a SQL server. Leveraging a comprehensive stack of Azure services, including Azure Data Factory (ADF), Azure Blob Storage, and Azure Databricks, we aim to achieve the following objectives:

#### 1) Medallion Architecture Implementation:

- Ingest data into the Bronze layer, maintaining its raw state.
- Utilize Azure Databricks for data transformation, creating a Silver layer with validated, enriched data.
- Load the refined data into Delta tables in the Gold zone.

#### 2) Azure Databricks for Data Transformations:

- Leveraging PySpark notebooks for advanced data transformations.
- Implementing Fact and Dimension data modeling for efficient data handling.

#### 3) Azure Pipelines and Scheduling:

- Create end-to-end Azure Pipelines for data movement and transformation.
- Leverage Azure Data Factory for scheduling and orchestration.
- Implement email triggers to ensure pipeline resiliency and monitoring.


<!-- TECH STACK -->
## Tech Stack<a name="tech-stack"></a>

- 📜 Language: Python, SQL, Spark
- 📦 Package: PySpark
- 🌐 Services: Azure Data Factory (ADF), Azure Blob Storage (ADLS Gen2), and Azure Databricks, Logic Apps, Azure SQL Database


<!-- ARCHITECTURE DIAGRAM -->
## Architecture Diagram<a name="architecture-diagram"></a>
vuuiberb
2
3
4
5
6
7

