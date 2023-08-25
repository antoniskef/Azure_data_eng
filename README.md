# azure_data_eng

## Diagram 
![image](https://github.com/antoniskef/azure_data_eng/assets/93796754/0c08a252-5dec-4fea-83df-94a280a43b9f)

For educational reasons all these services are used 

## Data Lake Gen 2
I create a storage account that has a hierarchical namespace. Then I create a container with two directories (raw and transformed data).

## Data Factory 
Deploy a data factory for data ingestion. The source is the file "data" from this repository and the destination is the "raw data" directory of the azure data lake gen 2 that has been already created. 




