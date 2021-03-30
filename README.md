# Microsoft Data Engineering four-day instructor-led training deployment

This repo contains manual and automated deployment steps for lab environments used by the Microsoft Data Engineering four-day ILT training curriculum.

## Module directory

- Module 1 - Explore compute and storage options for data engineering workloads
  - [Lab 01 setup instructions](setup/01/lab-01-setup.md)
  - [Lab 02 setup instructions - step 1 of 2](setup/01/asa-workspace-deploy.md)
  - [Lab 02 setup instructions - step 2 of 2](setup/01/lab-02-deploy.md)
- Module 2 - Design and Implement the serving layer
  - [Lab setup instructions](setup/02/README.md)
- Module 3 - Data engineering considerations for source files
  - No lab setup
- Module 4 - Run interactive queries using serverless SQL pools
  - [Lab setup instructions](setup/04/README.md)
- Module 5 - Explore, transform, and load data into the Data Warehouse using Apache Spark
  - [Lab setup instructions](setup/04/README.md)
- Module 6 - Data exploration and transformation in Azure Databricks
  - [Lab setup instructions](setup/06/lab-01-setup.md)
- Module 7 - Ingest and load data into the Data Warehouse
  - [Lab setup instructions](setup/04/README.md)
- Module 8 - Transform data with Azure Data Factory or Azure Synapse Pipelines
  - [Lab setup instructions](setup/04/README.md)
- Module 9 - Integrate data from notebooks with Azure Data Factory or Azure Synapse Pipelines
  - [Lab setup instructions](setup/04/README.md)
- Module 10 - Optimize query performance with dedicated SQL pools in Azure Synapse
  - [Lab setup instructions](setup/04/README.md)
- Module 11 - Analyze and optimize Data Warehouse storage
  - [Lab setup instructions](setup/04/README.md)
- Module 12 - Support Hybrid Transactional Analytical Processing (HTAP) with Azure Synapse Link
  - [Lab setup instructions](setup/04/README.md)
- Module 13 - End-to-end security with Azure Synapse Analytics
  - [Lab setup instructions](setup/04/README.md)
- Module 14 - Real-time stream processing with Stream Analytics
  - [Lab setup instructions](setup/14/README.md)
- Module 15 - Create a stream processing solution with Event Hubs and Azure Databricks
  - [Lab setup instructions](setup/15/lab-01-setup.md)
- Module 16 - Build reports using Power BI integration with Azure Synapse Analytics
  - [Lab setup instructions](setup/04/README.md)
- Module 17 - Perform integrated Machine Learning processes in Azure Synapse Analytics
  - [Lab setup instructions - step 1 of 2](setup/17/asa-workspace-deploy.md)
  - [Lab setup instructions - step 2 of 2](setup/17/lab-01-deploy.md)

## Modules that can share the same Synapse workspace

- Synapse workspace named **asagaworkspaceSUFFIX** (where SUFFIX is a unique id provided during setup):
  - Module 1
  - Module 17
- Synapse workspace named **asaworkspaceSUFFIX**:
  - Module 4
  - Module 5
  - Module 7
  - Module 8
  - Module 9
  - Module 10
  - Module 11
  - Module 12
  - Module 13
  - Module 16
- Requires own Synapse workspace (not shared):
  - Module 2
  - Module 14

## Modules that can share the same Azure Databricks workspace

- Module 1
- Module 6
- Module 15
