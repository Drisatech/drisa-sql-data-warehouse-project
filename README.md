# Data Warehouse and Analytics Project

Welcome to the Data Warehouse and Analytics Project repository! 🚀
This project showcases a complete end-to-end data engineering and analytics solution, demonstrating modern data warehouse design, ETL pipeline development, and analytical reporting.

It serves as a portfolio project to illustrate technical proficiency in data architecture, data modeling, and Power BI analytics — following industry best practices for scalability, governance, and performance.

---

# 🏗️ Data Architecture Overview

The solution adopts the Medallion Architecture (Bronze → Silver → Gold) for structured, modular data processing.


1. Bronze Layer – Ingests raw data directly from source systems (CSV files) into SQL Server for persistence.


2. Silver Layer – Performs data cleansing, standardization, and normalization to improve consistency and accuracy.


3. Gold Layer – Models business-ready data into a star schema, optimized for analytics and reporting in Power BI.

---

# 📖 Project Summary

This project highlights the following major components:

1. Data Architecture: Designed a scalable data warehouse using Medallion principles for modular data refinement.


2. ETL Pipelines: Developed robust ETL processes for data extraction, transformation, and loading using SQL scripts.


3. Data Modeling: Created dimensional models (fact and dimension tables) to support analytical queries.


4. Analytics & Reporting: Built Power BI dashboards and SQL-based reports to extract actionable business insights.


# 🎯 Key Skills Demonstrated

Data Warehousing & Architecture

ETL Development

SQL Server (SSMS / T-SQL)

Power BI Reporting

Data Modeling (Star Schema Design)

Data Quality & Governance

---

# 🛠️ Tools & Technologies

Category	Tools Used

Database & ETL	SQL Server Express, SSMS
Visualization	Power BI
Data Modeling	Draw.io
Documentation	Notion, Markdown
Version Control	Git & GitHub


## Additional resources:

Datasets Folder – Contains raw CSV data used for ingestion

Docs Folder – Architectural diagrams and documentation

SQL Server Express Download

SSMS Download

---

# 🚀 Project Requirements

Phase 1 – Data Engineering: Building the Data Warehouse

Objective

Design and deploy a modern SQL-based data warehouse that consolidates sales and customer data for analytics and reporting.

Specifications

Import datasets from two source systems (ERP and CRM) in CSV format.

Perform data cleansing and transformation to ensure consistency.

Integrate both data sources into a unified, query-optimized schema.

Focus on current data without historization requirements.

Deliver clear data documentation and schema design for analytics teams.

---

# Phase 2 – Business Intelligence & Analytics

## Objective

Deliver SQL and Power BI-based insights covering:

Customer behavior and segmentation

Product performance metrics

Sales trend analysis


These insights empower stakeholders to make data-driven business decisions effectively.

Refer to docs/requirements.md for technical details.


---

# 📂 Repository Structure

data-warehouse-analytics-project/
│
├── datasets/                           # Source datasets (ERP and CRM)
├── docs/                               # Architecture, design, and documentation
│   ├── data_architecture.drawio
│   ├── data_models.drawio
│   ├── etl.drawio
│   ├── data_flow.drawio
│   ├── data_catalog.md
│   ├── naming-conventions.md
│
├── scripts/                            # SQL scripts for ETL & transformations
│   ├── bronze/                         # Raw ingestion
│   ├── silver/                         # Cleansing & transformation
│   ├── gold/                           # Analytical modeling
│
├── tests/                              # Validation & data quality checks
├── README.md                           # Project documentation
├── LICENSE                             # Open-source license


---

## 💡 Key Takeaways

This project validates end-to-end data warehouse design and analytics delivery using Microsoft’s data stack.
It demonstrates the ability to:

Design and implement scalable ETL pipelines.

Model relational data for analytics.

Develop interactive Power BI reports.

Document data lineage and architecture effectively.


---

## ☕ Connect with Me

👋 Hi there! I’m Aliyu Idris Adeiza, a Data Engineer & Materials Science Engineer passionate about leveraging data to drive business and engineering innovation.

💼 Assistant Technical Secretary, Nigerian Society of Engineers (NSE), Ajaokuta Branch

🌐 Founder, DRISA Engineering & Infotech Solutions


Let’s connect and collaborate on data-driven projects:


---

## 🛡️ License

This project is licensed under the MIT License.
You are free to use, modify, and share this repository with proper attribution.


---

## 🌟 Closing Note

This project reflects my commitment to data engineering excellence, Azure ecosystem expertise, and practical problem-solving in real-world scenarios.
It also demonstrates the technical and analytical competencies I aim to bring into your Data Engineering team.
