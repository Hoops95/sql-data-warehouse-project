# sql-data-warehouse-project
Building a modern data warehouse with SQL Server, including ETL processes, data modeling, and analytics.

# Data Warehouse and Analytics Project 🚀

Welcome to the Data Warehouse and Analytics Project repository!  
This project demonstrates a complete end-to-end data warehousing and analytics solution — from raw data ingestion to generating actionable business insights.

Designed as a practical portfolio project, it highlights **industry best practices** in:
- Data Engineering
- Data Warehousing
- ETL/ELT Pipelines
- Data Modeling (Star Schema / Snowflake)
- Business Intelligence & Analytics

---

## 📊 Project Architecture

- **Source Systems:** CRM, ERP
- **ETL Tool:** SSIS
- **Data Warehouse:** SQL Server
- **Modeling:** Star Schema (Facts & Dimensions)
- **BI Tool:** Power BI

---

## 🧠 Medallion Architecture (Mediation Approach)

This project follows the **Medallion Architecture** (Mediation Approach) to build a scalable and well-structured data warehouse:

### 🥉 Bronze Layer – Raw Data
- Raw data ingestion from CRM and ERP systems  
- No transformations applied  
- Maintains original source data for auditing and traceability

### 🥈 Silver Layer – Cleaned & Standardized Data
- Data cleaning and validation  
- Removing duplicates and handling missing values  
- Standardized formats (dates, naming, IDs, etc.)
- Unified and conformed data model

### 🥇 Gold Layer – Analytics Ready Data
- Fact and Dimension tables built using Star Schema  
- Business rules applied  
- Final curated data for dashboards and insights in Power BI

---

## 🏗️ Data Pipeline Workflow

1. Extract data from source systems  
2. Load raw data into Bronze layer  
3. Clean, validate, and standardize data in Silver layer  
4. Transform into fact & dimension tables in Gold layer  
5. Build interactive dashboards & reports

---


