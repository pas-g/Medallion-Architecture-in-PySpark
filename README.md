# Medallion Architecture in PySpark

This repository demonstrates the implementation of the Medallion Architecture using PySpark. The project follows a structured approach to data processing, with data flowing through three key layers: Bronze, Silver, and Gold.

Purpose
The primary goal of this repository is to showcase the use of the Medallion Architecture in a Lakehouse environment. The process starts by ingesting raw data from a local file, which is uploaded into the "FILE" folder of the Lakehouse. The data is then:

1. Bronze Layer (Raw Data): The raw data is ingested and stored in its original form.
2. Silver Layer (Cleaned Data): The raw data undergoes necessary cleaning and transformation processes to make it suitable for analysis.
3. Gold Layer (Curated Data): The cleaned data is further processed into structured dimensions and fact tables, providing high-quality, analytical-ready data.
   
All these layers are processed within a single Lakehouse, ensuring an efficient and streamlined data pipeline.

this exercise can be found at:
  https://microsoftlearning.github.io/mslearn-fabric/Instructions/Labs/03b-medallion-lakehouse.html
