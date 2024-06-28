# Analytics Pipeline for Olympic Data Using MS Azure

## Overview
This project involves creating a comprehensive data engineering pipeline using Microsoft Azure services to handle data ingestion, transformation, storage, and visualization.

## Steps Involved

### 1. Data Ingestion
**Tool Used:** Azure Data Factory

**Description:**
- Developed a dynamic pipeline to transfer raw data from an on-premise SQL Server to Azure Data Lake Storage Gen2.
- Utilized Azure Data Factory's linked services for seamless data integration.
- Ensured efficient data movement with dynamic configurations.

### 2. Data Transformation
**Tool Used:** Azure Databricks

**Description:**
- Transformed raw data from Azure Data Lake Gen2 using PySpark and SQL in Azure Databricks.
- Established a connection between Azure Databricks and the storage account using an app registration key.
- Reloaded the transformed data back into Azure Data Lake Gen2 for further processing.

### 3. Data Analytics
**Tool Used:** Azure Synapse Analytics

**Description:**
- Transferred the transformed data from Azure Data Lake Gen2 to Azure Synapse Analytics.
- Structured and converted data to meet specific business requirements.
- Enabled efficient data analysis and reporting within Azure Synapse.

### 4. Data Visualization
**Tool Used:** Power BI

**Description:**
- Integrated the final transformed data with Power BI.
- Created interactive dashboards and reports for data visualization.
- Provided clear insights and supported data-driven decision-making processes.

## Technologies and Tools Used
- **Azure Data Factory:** For data ingestion.
- **Azure Data Lake Storage Gen2:** For data storage.
- **Azure Databricks:** For data transformation.
- **Azure Synapse Analytics:** For data analytics.
- **Power BI:** For data visualization.

## How to Use
1. **Data Ingestion:**
   - Set up Azure Data Factory with linked services to connect to your on-premise SQL Server and Azure Data Lake Storage Gen2.
   - Configure dynamic pipelines for efficient data transfer.

2. **Data Transformation:**
   - Use Azure Databricks to transform data stored in Azure Data Lake Gen2.
   - Apply PySpark and SQL transformations as per your business requirements.
   - Reload the transformed data back into Azure Data Lake Gen2.

3. **Data Analytics:**
   - Move the transformed data to Azure Synapse Analytics.
   - Structure and convert the data for analysis and reporting.

4. **Data Visualization:**
   - Connect Power BI to Azure Synapse Analytics.
   - Develop interactive dashboards and reports to visualize the data.

## Conclusion
This project demonstrates the effective use of Microsoft Azure services to build a robust data engineering pipeline, enabling efficient data ingestion, transformation, storage, and visualization. The interactive dashboards created in Power BI provide valuable insights and support data-driven decision-making processes.


