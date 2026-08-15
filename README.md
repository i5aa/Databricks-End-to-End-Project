**📌 Project Overview**

This project implements a modern Medallion Architecture (Bronze → Silver → Gold) on Azure Databricks, ingesting raw data from Azure Data Factory, transforming it with PySpark and Delta Live Tables, modeling it into a Star Schema, and serving it to Power BI through a Databricks SQL Warehouse.

The pipeline is designed to simulate a real-world, production-style analytics platform — including incremental data loads, governed access via Unity Catalog, and version-controlled orchestration through GitHub.
