# azure_data_eng

## Diagram 
![image](https://github.com/antoniskef/azure_data_eng/assets/93796754/0b398964-a485-4a25-8f95-99b0fa5e4d22)

## Data Lake Gen 2
I create a storage account that has a hierarchical namespace. Then I create a container with two directories (raw and transformed data).

## Data Factory 
Deploy a data factory for data ingestion. The source is the file "data" from this repository and the destination is the "raw data" directory of the azure data lake gen 2 that has been already created. 

![image](https://github.com/antoniskef/azure_data_eng/assets/93796754/c8ff17ab-96d1-4f3a-b9a2-c432e2f0b63c)

## Azure Databricks 
Create a cluster for data transformation. 

