# Tokyo-Olympic-Azure-Data-Engineering-Project

![image](https://github.com/jaisbhavana/Tokyo-Olympic-Azure-Data-Engineering-Project/blob/main/Doc1.png)


**Project Title: Olympic Data Analysis with Azure**

**Overview** <br>
This project demonstrates how to collect, transform, and analyze Olympic data using Azure services, including Azure Data Factory, Azure Data Lake Storage Gen 2, Azure Databricks, and Azure Synapse Analytics. The goal is to showcase an end-to-end data pipeline for data extraction, transformation, and analysis.

**Project Steps**

**Step 1: Data Collection from Kaggle and GitHub**

Data Sources: Download Olympic data from Kaggle and create a folder structure for your project on GitHub.
GitHub Repository: Upload the downloaded data into your GitHub repository. This ensures version control and collaboration.

**Step 2: Creating Azure Data Factory (ADF)** <br>
Azure Data Factory: Create an Azure Data Factory instance in your Azure account.
Pipeline Definition: Define a pipeline within ADF for data movement and transformation.
Linked Services: Set up linked services to connect ADF with your GitHub repository.

**Step 3: Data Extraction and Storage in Azure Data Lake Storage Gen 2 (ADLS)** <br>
GitHub Data Extraction: Configure ADF to extract data from your GitHub repository.
ADLS Gen 2: Use the defined pipeline to move the data to Azure Data Lake Storage Gen 2.
Data Organization: Organize the data in ADLS to maintain structure and accessibility.

**Step 4: Data Transformation using Azure Databricks** <br>
Databricks Setup: Set up an Azure Databricks cluster in your Azure account.
Data Ingestion: Ingest the data from ADLS into Databricks.
Data Transformation: Perform data transformations, cleansing, and enrichment using Databricks notebooks.
Advanced Analytics: Execute advanced analytics, such as aggregations and statistical analyses.

**Step 5: Storing Transformed Data Back to ADLS** <br>
Data Storage: Save the transformed data from Databricks back into Azure Data Lake Storage Gen 2.
Data Organization: Ensure that the data is appropriately organized and labeled for easy retrieval.

**Step 6: Utilizing Azure Synapse Analytics (formerly SQL Data Warehouse)** <br>
Azure Synapse Analytics: Create an Azure Synapse Analytics instance in your Azure account.
Schema Design: Design the schema and tables to accommodate your transformed data.
Data Loading: Load the data from ADLS into Synapse Analytics for analysis.

**Step 7: Data Exploration and Analysis** <br>
SQL Queries: Develop complex SQL queries within Azure Synapse Analytics to explore insights.
Analysis: Perform historical analysis, identify patterns, and extract meaningful information from the Olympic data.

Getting Started <br>
To replicate this project, follow the steps outlined above and refer to the detailed documentation provided within each step's directory in this repository.



**Prerequisites <br>
Azure Account with appropriate subscriptions.
Azure Data Factory, Databricks, and Synapse Analytics instances set up.
GitHub account for version control and data storage.**

 








