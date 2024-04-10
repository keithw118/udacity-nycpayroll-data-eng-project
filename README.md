Summary of Data Lakehouse/Azure Databricks Project: 

The goal of this project was to develop a data lake solution using Azure Databricks using a lake house architecture. I accomplished the following:

- Designed a star schema based on the business outcomes below

- Import the data into Azure Databricks using Delta Lake to create a Bronze data store

- Created a gold data store in Delta Lake tables

- Transformed the data into the star schema for a Gold data store

I implemented these requirements by creating notebooks in the Azure Databricks workspace.

Below are the business outcomes I worked to find:

1. Analyze how much time is spent per ride
- Based on date and time factors such as day of week and time of day
- Based on which station is the starting and / or ending station
- Based on age of the rider at time of the ride
- Based on whether the rider is a member or a casual rider
2. Analyze how much money is spent
- Per month, quarter, year
- Per member, based on the age of the rider at account start

Summary of NYC Payroll Data Project:

- Analyze how the City's financial resources are allocated and how much of the City's budget is being devoted to overtime.

- Make the data available to the interested public to show how the City’s budget is being spent on salary and overtime pay for all municipal employees

Summary of Work:

- Used Azure Data Factory to create Data views in Azure SQL DB from the source data files in DataLake Gen2. 

- Built dataflows and pipelines to create payroll aggregated data that will be exported to a target directory in DataLake Gen2 storage where Synapse Analytics external table would be built.

Azure Resources involved:

- Azure Data Lake Gen2
- Azure SQL DB
- Azure Data Factory
- Azure Synapse Analytics
