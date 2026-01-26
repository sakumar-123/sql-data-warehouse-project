
📊 Data Warehouse & Analytics Project

Welcome to my Data Warehouse and Analytics Project repository! 🚀
This project showcases an end-to-end data warehousing solution — from raw data ingestion to analytical reporting. It is designed as a hands-on portfolio project demonstrating practical data engineering and analytics skills using SQL Server.

🏗️ Data Architecture

This project follows the Medallion Architecture pattern with Bronze, Silver, and Gold layers.

🔹 Bronze Layer

Stores raw data exactly as received from source systems. Data is ingested from CSV files into SQL Server without transformation.

🔹 Silver Layer

Performs data cleansing, validation, standardization, and transformation to make the data analysis-ready.

🔹 Gold Layer

Contains business-ready data modeled into a star schema, optimized for reporting and analytics.

📖 Project Overview

This project demonstrates:

Designing a modern data warehouse using layered architecture

Building ETL pipelines using SQL

Performing data cleaning and transformation

Creating fact and dimension tables for analytics

Writing analytical SQL queries for business insights

🎯 This project highlights my skills in:

SQL Development

Data Warehousing

Data Modeling

ETL & Data Transformation

Data Analytics

🛠️ Tools & Technologies Used
Tool	Purpose
SQL Server Express	Database engine for the warehouse
SQL Server Management Studio (SSMS)	Database development & querying
CSV Files	Source data (ERP & CRM systems)
Draw.io	Data architecture and model diagrams
Git & GitHub	Version control and project hosting
🚀 Project Requirements
🏗️ Building the Data Warehouse (Data Engineering)

Objective:
Develop a structured data warehouse that consolidates sales data from multiple systems for reporting and analysis.

Key Tasks:

Import data from ERP and CRM CSV sources

Clean and validate data to resolve quality issues

Transform raw data into structured, analysis-ready tables

Design a star schema for reporting

Document the data model clearly for business and analytics users

📊 Analytics & Reporting (Data Analysis)

Objective:
Use SQL queries to generate business insights related to:

Customer Behavior

Product Performance

Sales Trends

These insights help support data-driven decision-making.

More details can be found in:
📄 docs/requirements.md

📂 Repository Structure
data-warehouse-project/
│
├── datasets/                   # Raw ERP and CRM datasets (CSV files)
│
├── docs/                       # Project documentation & architecture
│   ├── data_architecture.drawio
│   ├── data_flow.drawio
│   ├── data_models.drawio
│   ├── data_catalog.md
│   ├── naming-conventions.md
│
├── scripts/                    # SQL scripts for each warehouse layer
│   ├── bronze/                 # Raw data loading scripts
│   ├── silver/                 # Data cleaning & transformation scripts
│   ├── gold/                   # Analytical model creation scripts
│
├── tests/                      # Data quality and validation queries
│
├── README.md                   # Project documentation
├── LICENSE                     # License information
└── .gitignore                  # Files ignored by Git

🧠 Key Learning Outcomes

Through this project, I practiced:

✔ Designing layered data architecture
✔ Writing SQL transformations for data cleansing
✔ Handling data quality issues (NULLs, invalid dates, incorrect calculations)
✔ Building fact and dimension tables
✔ Creating analysis-ready datasets for reporting

👨‍💻 About Me

Sai Kumar Embadi | Data Engineer with Analytics Expertise
Building data pipelines, transforming raw data, and enabling insights for smarter business decisions.

This project is part of my journey in strengthening my skills in:

SQL & Data Warehousing

Data Modeling

Analytics & Reporting

🔗 Connect With Me

💼 LinkedIn: (https://www.linkedin.com/in/sai-kumar-embadi/)

💻 GitHub: (https://github.com/sakumar-123)

🗂️ Portfolio / Notion: (https://www.notion.so/Data-Warehouse-Project-2e3b607b7fd080969cf0cc76a06aa760)

🛡️ License

This project is licensed under the MIT License.
You are free to use, modify, and share this project with proper attribution.
