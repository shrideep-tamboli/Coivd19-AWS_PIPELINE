# AWS-Data_Engineering_Project
## Overview:
This project aims to build a data lake by gathering raw data in AWS S3, creating a data model from the raw data to make it structured, and warehousing the structured data in AWS Redshift.
## Project Goals:
1. Data Ingestion: Gathering all the required data in raw format to create a data lake.
2. ETL Process: Extracting data from the data lake for transformation and Loading back the transformed data to the warehouse.
3. Data Modelling: Modelling the raw data to fact and dimension tables in the transformation process.
4. Cloud: Processing large volumes of data comes with the cost of latency in local systems therefore; AWS Cloud to the rescue.
5. Data Warehousing: To make the data available in a structured format for data analysts or stakeholders for further analysis and reporting.
6. Reporting & Analysis: Some basic EDA to demonstrate end-end data project.
## Services used:
1. Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
2. AWS IAM: This is nothing but identity and access management which enables us to manage access to AWS services and resources securely.
3. AWS Glue: A serverless data integration service that is like an ETL Tool.
4. AWS Athena: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.
5. AWS Redshift: A data warehousing and OLAP service provided by Amazon.
