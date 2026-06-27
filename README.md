## 📊 Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics** project repository! 🚀

This project showcases an end-to-end data warehousing and analytics solution, covering the complete workflow from **data ingestion** and **transformation** to **warehouse design** and **analytical reporting** . It demonstrates industry best practices in **data engineering**, **data modeling**, and **SQL-based analytics** to transform raw data into actionable business insights.

---

## 🛠️ Tech Stack

- 🐘 PostgreSQL
- 📝 SQL
- 📂 CSV Files
- 🏛️ Medallion Architecture
- ⭐ Star Schema
- 📊 Data Warehousing
---

🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:
1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into PostgreSQL Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

---
## 📖 Project Overview

This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers.
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.
---

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective

Develop a modern data warehouse using **PostgreSQL** to consolidate sales data and enable analytical reporting and data-driven decision-making.

#### Specifications

* **Data Sources**: Imported data from two source systems (ERP and CRM) provided as CSV files.
* **Data Quality**: Cleaned and resolved data quality issues before analysis.
* **Integration**: Combined both data sources into a single, user-friendly data model optimized for analytical queries.
* **Scope**: Focused on the latest available dataset; historization of data was not implemented.
* **Documentation**: Documented the data model to support both business users and analytics teams.

---

### 📊 Analytics & Reporting (Data Analysis)

#### Objective

Develop SQL-based analytics in **PostgreSQL** to generate detailed insights into:

* **Customer Behavior**
* **Product Performance**
* **Sales Trends**

These insights provide key business metrics that support informed and strategic decision-making.
---

## 📝 License

This project is licensed under the **MIT License**.
