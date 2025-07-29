# Data-factory-with-Devops

This project demonstrates a solution in Azure Fabric with 3 pipelines that takes 3 different data sources and extracts the data to an azure DataLake container classified as a bronze layer.


![image](assets/DataFactory.png/)

## 📖 Project Overview
This project involves:

1. **Api_ingestion**: extracting data from Github.
2. **On premises ingestion**: Extracting csv files from a computer)
3. **SQL ingestion**: database ingestion with incrementing loading, it takes a table and migrates the table based on a date parameter, the data is write in parquet format.
4. ** Logic App**: a logic app that checks if the SQL ingestion was done perfectly, otherwise, it triggers an email specifying the error and pipeline details


   
#### Objective
Develop a parent Pipeline that contains the 3 pipelines described before. Extracts the data to load it into an azure DataLake over the bronze layer container.

#### Specifications
- **Data Sources**: 
- **Data Quality**: 
- **Integration**: 
- **Scope**: 
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.
