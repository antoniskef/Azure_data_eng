# azure_data_eng

## Diagram 
![image](https://github.com/antoniskef/azure_data_eng/assets/93796754/0b398964-a485-4a25-8f95-99b0fa5e4d22)

## Data Lake Gen 2
I create a storage account that has a hierarchical namespace. Then I create a container with two directories (raw and transformed data).

## Data Factory 
Deploy a data factory for data ingestion. The source is the file "data" from this repository and the destination is the "raw data" directory of the azure data lake gen 2 that has been already created. 

![image](https://github.com/antoniskef/azure_data_eng/assets/93796754/c8ff17ab-96d1-4f3a-b9a2-c432e2f0b63c)

## Azure Databricks 
Firstly create an azure databricks workspace and then create a cluster. After create a connection between data lake (raw data) with databricks using app registrations. Finally transform data using spark (data_engineering_1.ipynb).

## Azure synapse analytics 
Azure synapse analytics is used for data analysis with sql.
![image](https://github.com/antoniskef/azure_data_eng/assets/93796754/a6542569-aec1-480d-b98c-80792a4a4220)
Azure synapse analytics could have been used for data ingestion and transformation too, but in order to learn how to connnect different services the above procedure was chosen.
