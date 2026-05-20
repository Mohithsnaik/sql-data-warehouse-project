<p align="center">
  <span style="font-size:32px;"><b>sql-data-warehouse-project</b></span>
</p>

Building a modern data warehouse with SQL Server, including ETL processes, data modeling, and analytics.

<br>

<b style="font-size:28px;">Data Architecture</b>

<br><br>

<b>Bronze Layer</b>

Stores raw data as-is from source systems.  
Data is ingested from CSV files into SQL Server with minimal or no transformations.

<br>

<b>Silver Layer</b>

Performs data cleansing, standardization, normalization, and enrichment processes to prepare structured data for analytics.

<br>

<b>Gold Layer</b>

Provides business-ready data modeled into star schema and aggregated tables for reporting, BI dashboards, ad-hoc SQL queries, and machine learning.
