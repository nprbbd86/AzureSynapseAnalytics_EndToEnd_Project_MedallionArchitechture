# Azure Synapse Analytics End-to-End Project - Medallion Architecture

Welcome to my Azure Data Analytics project, where I leverage Azure Synapse services to analyze NYC Green taxi trips data. This project is aimed at providing valuable insights by implementing the Medallion Architecture, a data structuring framework consisting of three layers: Raw(Bronze), Structured(Silver), and Curated(Gold). Each layer has its unique purpose, making data processing more efficient and insightful.

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [Project Goals](#projectgoals)
* [Tech Stack](#tech-stack)
* [Architecture Diagram](#architecture-diagram)
* [Dataset Used](#datasetused)
* [Project Codes and Files](#projectfiles)
* [Fact Dimension Tables - Data Modelling](#datamodelling)


<!-- Project Goals -->
## Project Goals<a name="projectgoals"></a>

The primary goal of this GitHub portfolio project is to implement robust analytics and insights on NYC Green taxi trips data. Leveraging Azure Synapse Analytics, we aim to achieve the following objectives:

- Ingest data into the Bronze layer, maintaining its raw state.
- Utilize Azure Synapse Analystics for data transformation, creating a Silver layer with validated, enriched data.
- Load the refined data in the Gold zone.
- Implementing Fact and Dimension data modeling for efficient data handling.
- Create end-to-end Azure Pipelines for data movement and transformation.


<!-- TECH STACK -->
## Tech Stack<a name="tech-stack"></a>

- 📜 Language: SQL , Spark
- 📦 Package: 
- 🌐 Services: Azure Synapse


<!-- ARCHITECTURE DIAGRAM -->
## Architecture Diagram<a name="architecture-diagram"></a>
![Picture](https://github.com/nprbbd86/AzureSynapseAnalytics_EndToEnd_Project_MedallionArchitechture/blob/main/Project%20resources/Solution%20Architechture.png)



<!-- Dataset Used -->
## Dataset Used<a name="datasetused"></a>
Here is the link to reference dataset:
https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
 
Below is the list of datasets : 

1- Taxi Zone (CSV) <br>
2- Calendar (CSV)  <br>
3- Trip Type (TSV)  <br>
4- Rate Code (JSON)  <br> 
5- Payment Type (JSON)  <br>
6- Vendor (CSV)  <br>
7- Trip Data (Parquet,CSV,Delta)  <br>



<!-- Project Codes and Files -->
## Project Codes and Files<a name="projectfiles"></a>

- For Configuration : https://github.com/nprbbd86/AzureSynapseAnalytics_EndToEnd_Project_MedallionArchitechture/tree/main/Project%20resources/SQL%20scripts/config
- Data Discovery and exploration : https://github.com/nprbbd86/AzureSynapseAnalytics_EndToEnd_Project_MedallionArchitechture/tree/main/Project%20resources/SQL%20scripts/Data%20discovery%20and%20exploration
- Creating External Tables : https://github.com/nprbbd86/AzureSynapseAnalytics_EndToEnd_Project_MedallionArchitechture/tree/main/Project%20resources/SQL%20scripts/Creating%20external%20tables


<!-- Fact Dimension Tables - Data Modelling -->
## Fact Dimension Tables - Data Modelling<a name="datamodelling"></a>
![Picture](https://github.com/nprbbd86/AzureSynapseAnalytics_EndToEnd_Project_MedallionArchitechture/blob/main/Project%20resources/Data%20Model.png)


