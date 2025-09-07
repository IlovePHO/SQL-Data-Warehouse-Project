# Data Warehouse and Analytics Project

Welcome to the Data Warehouse and Analytics Project repository! 🚀
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.


# Data Architecture

1. Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.


# Project Overview

This project involves:

1. Data Architecture: Designing a Modern Data Warehouse Using Medallion Architecture Bronze, Silver, and Gold layers.
2. ETL Pipelines: Extracting, transforming, and loading data from source systems into the warehouse.
3. Data Modeling: Developing fact and dimension tables optimized for analytical queries.
4. Analytics & Reporting: Creating SQL-based reports and dashboards for actionable insights.


# This repository is an excellent resource for professionals and students looking to showcase expertise in:

・SQL Development
・Data Architect
・Data Engineering
・ETL Pipeline Developer
・Data Modeling
・Data Analytics


# Project Requirements


Building the Data Warehouse (Data Engineering)

Objective

Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

Specifications:

・Data Sources: Import data from two source systems (ERP and CRM) provided as CSV files.
・Data Quality: Cleanse and resolve data quality issues prior to analysis.
・Integration: Combine both sources into a single, user-friendly data model designed for analytical queries.
・Scope: Focus on the latest dataset only; historization of data is not required.
・Documentation: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

# Repository Structure


+---datasets
|   +---source_crm
|   |       cust_info.csv
|   |       prd_info.csv
|   |       sales_details.csv
|   |       
|   \---source_erp
|           CUST_AZ12.csv
|           LOC_A101.csv
|           PX_CAT_G1V2.csv
|           
+---scripts
|   |   init_database.sql
|   |   
|   +---bronze
|   |       ddl_bronze.sql
|   |       proc_load_bronze.sql
|   |       
|   +---gold
|   |       ddl_gold.sql
|   |       
|   \---silver
|           ddl_silver.sql
|           proc_load_silver.sql
|           
\---tests
        quality_checks_gold.sql
        quality_checks_silver.sql




"# SQL-Data-Warehouse-Project" 
"# SQL-Data-Warehouse-Project" 
