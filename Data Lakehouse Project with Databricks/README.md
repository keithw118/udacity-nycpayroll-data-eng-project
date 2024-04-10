Summary: 

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
