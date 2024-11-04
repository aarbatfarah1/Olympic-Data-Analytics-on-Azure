# Olympic Data Analytics

## Project Overview
This project is an Azure-based, end-to-end data engineering pipeline developed to analyze Olympic data. Leveraging a suite of Azure services, we built a solution to ingest, transform, and visualize data, offering insights into Olympic events, athletes, and historical performance.

## Architecture Diagram
![Architecture Diagram](Olympic_Diagram.png)  
*Replace the above path with the correct path to your architecture diagram.*

## Data Source
The Olympic data was sourced from Kaggle, including detailed records of Olympic events, athlete profiles, and results across multiple years.

## Project Components

1. **Data Integration**
   - **Azure Data Factory**: Ingests data from Kaggle and loads it into the raw data storage.

2. **Raw Data Store**
   - **Azure Data Lake Gen 2**: Stores raw data for transformation.

3. **Data Transformation**
   - **Azure Databricks**: Cleanses and transforms raw data before storing it in a structured format.

4. **Transformed Data Store**
   - **Azure Data Lake Gen 2**: Holds cleaned data, ready for analysis.

5. **Analytics**
   - **Azure Synapse Analytics**: Enables analytical querying and data exploration.

6. **Visualization**
   - **Power BI**: Provides interactive dashboards to visualize insights from Olympic data.

