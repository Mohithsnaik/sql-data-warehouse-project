# sql-data-warehouse-project
Building a modern data warehouse with SQL Server, including ETL Processes, data modeling and analytics.

** Data Architecture

The project follows the **Medallion Architecture** approach with **Bronze, Silver, and Gold** layers.

**Bronze Layer**

Stores raw data as-is from source systems.  
Data is ingested from CSV files into SQL Server with minimal or no transformations.

**Silver Layer**

Performs data cleansing, standardization, normalization, and enrichment processes to prepare structured data for analytics.

**Gold Layer**

Provides business-ready data modeled into star schema and aggregated tables for reporting, BI dashboards, ad-hoc SQL queries, and machine learning.
### Data Flow
```text
Source Systems → Bronze → Silver → Gold → Analytics & Reporting
