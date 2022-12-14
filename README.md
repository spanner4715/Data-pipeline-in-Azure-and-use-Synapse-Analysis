# Data-pipeline-in-Azure-and-use-Synapse-Analysis
Build a data pipeline in Azure using Azure Synapse Analytics, Azure Storage and Azure Synapse SQL pool  
Perform data analysis on the 2021 Olympics dataset & visualize data in charts in Power BI 
### 1. Azure Storage
Create a new database and upload 2021 Olympics various data objects
### 2. Azure Synapse SQL Pool
A dedicated SQL pool can represent a collection of analytics resources provided when using Synapse SQL  
By creating a dedicated SQL pool, it's available to use PolyBase-T-SQL queries to import big data  and leverage the distributed query engine to perform analytics
### 3. Azure Synapse workspace
The workspace stores data in Apache Spark tables.

Approach:

1. Create an azure synapse analytics workspace, dedicated sql pool (DW) and a storage account, upload data files into a container
![image](https://user-images.githubusercontent.com/103509243/198841506-0347e1dd-bf44-4f03-82d6-79beaa4fe90b.png)

2. Create table structure in SQL pool (Telling the system what does data look like)
![image](https://user-images.githubusercontent.com/103509243/198843531-26c50717-3a57-42fe-942d-ae3dae8ce6af.png)

3. Create a data pipeline to ingest data from azure storage into SQL pool tables
![datapipeline](https://user-images.githubusercontent.com/103509243/192183079-c13acb1e-8672-4724-a8a8-8884419a8a83.png)

6. Load data from SQL pool tables into Power BI (Create a linked service to PowerBI)
![image](https://user-images.githubusercontent.com/103509243/198848908-43d4f927-3f4e-433b-8ff9-ed72281c36c0.png)

7. Data Modelling in Power BI
![image](https://user-images.githubusercontent.com/103509243/198849068-8737c746-7fbd-4bbb-a861-13b560744a83.png)

## Data visualization & Analysis
![analysis](https://user-images.githubusercontent.com/103509243/192183263-866eb150-f475-45dd-9012-a79b55edea89.png)
![Pie chart](https://user-images.githubusercontent.com/103509243/192183292-aba2c5c8-97cd-40e3-b129-32f992784b59.png)
