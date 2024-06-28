Project: Analytics Pipeline for Olympic Data Using MS Azure
Overview:
This project involved creating a comprehensive data engineering pipeline using Microsoft Azure services to handle data ingestion, transformation, storage, and visualization.

Steps Involved:

Data Ingestion:

Tool Used: Azure Data Factory
Description:
Developed a dynamic pipeline to transfer raw data from an on-premise SQL Server to Azure Data Lake Storage Gen2.
Utilized Azure Data Factory's linked services for seamless data integration.
Ensured efficient data movement with dynamic configurations.
Data Transformation:

Tool Used: Azure Databricks
Description:
Transformed raw data from Azure Data Lake Gen2 using PySpark and SQL in Azure Databricks.
Established a connection between Azure Databricks and the storage account using an app registration key.
Reloaded the transformed data back into Azure Data Lake Gen2 for further processing.
Data Analytics:

Tool Used: Azure Synapse Analytics
Description:
Transferred the transformed data from Azure Data Lake Gen2 to Azure Synapse Analytics.
Structured and converted data to meet specific business requirements.
Enabled efficient data analysis and reporting within Azure Synapse.

Data Visualization:
Tool Used: Power BI
Description:
Integrated the final transformed data with Power BI.
Created interactive dashboards and reports for data visualization.
Provided clear insights and supported data-driven decision-making processes.
Technologies and Tools Used:
