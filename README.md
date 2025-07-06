# Databricks ELT Pipeline: Sales Data
This project demonstrates an ELT pipeline built on Databricks using Apache Spark and Delta Lake with a medallion architecture (Bronze, Silver, Gold layers). It ingests, cleans, and aggregates sales data to prepare it for analytics.

## Features
- Ingests raw sales transactions data into the Bronze layer (Delta table).
- Cleans and transforms data in the Silver layer.
- Aggregates sales by country in the Gold layer.
- Uses Apache Spark for distributed processing.
- Data stored in Delta Lake format for performance and reliability.

## Technologies
- Databricks
- Apache Spark
- Delta Lake
- Python
- SQL
