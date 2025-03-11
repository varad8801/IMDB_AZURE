# IMDB Data Pipleline Analysis and Using Azure Cloud

## Project Overview

This project implements an end-to-end ETL (Extract, Transform, Load) data pipeline using Azure cloud services. The processed data is then analyzed and visualized using Power BI.

## Architecture Diagram

![Screenshot 2025-03-11 152941](https://github.com/user-attachments/assets/ab423e89-4504-4ab4-83d9-c00351899110)


## Technologies Used

- **Azure Data Factory (ADF)**: Extracts data from an on-premises SQL Server database and loads it into Azure Data Lake Gen2.
- **Azure Data Lake Gen2**: Stores raw, processed, and curated data in Bronze, Silver, and Gold layers.
- **Azure Databricks**: Performs data transformations and processing.
- **Azure Synapse Analytics**: Analyzes and optimizes the data for reporting.
- **Power BI**: Creates dashboards and visualizations for insights.
- **Azure Active Directory & Azure Key Vault**: Implements security and governance measures.

## ETL Flow

![ADF_Flowchart](https://github.com/user-attachments/assets/d24cf20a-93ea-4daa-8503-4b25e00f5ac8)


1. **Extraction**: Data is ingested from an on-premises SQL Server database into Azure Data Lake Gen2 via Azure Data Factory.
2. **Transformation**: Azure Databricks processes data through Bronze, Silver, and Gold layers.
3. **Loading**: The transformed data is loaded into Azure Synapse Analytics.

## Power BI Analysis

![Power bi SS](https://github.com/user-attachments/assets/df389477-b6a3-44e8-b9f6-1e621d905ca4)


Power BI connects to Azure Synapse Analytics to visualize trends, insights, and key metrics.

## Getting Started

1. Clone the repository:
   ```sh
   git clone https://github.com/varad8801/IMDB_AZURE.git
   ```
2. Configure Azure services and update necessary connection strings.
3. Run the ETL pipeline in Azure Data Factory.
4. Analyze data in Power BI.

## Future Enhancements

- Implement real-time data streaming.
- Automate monitoring and alerting.


---

Feel free to contribute by opening issues or submitting pull requests!


