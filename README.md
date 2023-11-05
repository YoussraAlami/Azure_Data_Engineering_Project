# Azure_Data_Engineering_Project
# Japan Visa Analysis: Azure End to End Data Engineering 🌐
This project provides an end-to-end data processing and visualization of visa numbers in Japan using PySpark and Plotly. The spark clusters are set up within a Docker container on Azure.


# System Architecture
![Sparkcluster_architecture](/Sparkcluster_architecture.png)



## 📈 Features
- **System Architecture**: The Spark master-worker architecture is set up in a Docker container on Azure.
- **Data Ingestion**: The script ingests the CSV file containing the visa numbers in Japan.
- **Data Cleaning**: The script standardizes column names, drops null columns, and corrects country names using fuzzy matching.
- **Data Transformation**: The data is further enriched by adding continent information for each country.
- **Data Visualization**: The cleaned and transformed data is visualized using Plotly Express to provide insights into visa trends in Japan.
