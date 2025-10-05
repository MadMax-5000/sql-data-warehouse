# Enterprise Data Warehouse & Analytics Solution

Welcome to the **Enterprise Data Warehouse & Analytics Solution** repository! 🎯  
This repository showcases an end-to-end data warehousing and analytics platform, covering everything from warehouse construction to insight generation.<br> 
Built as a comprehensive portfolio piece, it demonstrates professional-grade practices in data engineering and business intelligence.

---
## 🏗️ Architecture Design

This project implements the Medallion Architecture pattern with three distinct layers: **Bronze**, **Silver**, and **Gold**:
![Architecture Diagram](docs/data_architecture.png)

1. **Bronze Layer**: Contains unprocessed, raw data directly from source systems. Data flows from CSV files into SQL Server Database tables.
2. **Silver Layer**: Implements data quality improvements including cleansing, standardization, and normalization to create analysis-ready datasets.
3. **Gold Layer**: Contains refined, business-optimized data structured as a star schema for efficient reporting and analytics workloads.

---
## 📖 What's Inside

This solution encompasses:

1. **Architecture Design**: Implementation of Modern Data Warehouse principles using the Medallion Architecture with **Bronze**, **Silver**, and **Gold** tiers.
2. **Data Pipeline Development**: Building robust ETL processes to extract, transform, and load data from multiple sources.
3. **Dimensional Modeling**: Creating optimized fact and dimension tables tailored for analytical workloads.
4. **Business Intelligence & Reporting**: Developing SQL-driven reports and visualizations that deliver business value.

🎯 This repository serves as a valuable reference for individuals seeking to demonstrate proficiency in:
- Database Development with SQL
- Data Architecture & Design
- ETL & Data Pipeline Engineering  
- Dimensional & Star Schema Modeling  
- Business Intelligence & Analytics  

---

## 🛠️ Technology Stack & Resources:

All tools are available at no cost!
- **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads):** Free database engine for SQL Server deployment.
- **[SSMS - SQL Server Management Studio](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16):** Database management and development interface.
- **[GitHub](https://github.com/):** Create your GitHub account to maintain version control and share your work.
- **[Draw.io](https://www.draw.io/):** Create architectural diagrams, data models, and process flows.


---

## 🚀 Solution Objectives

### Data Warehouse Implementation (Engineering Focus)

#### Goal
Build a production-ready data warehouse on SQL Server to centralize sales information, supporting analytical workloads and business intelligence initiatives.

#### Technical Requirements
- **Source Systems**: Integrate data from dual sources (ERP and CRM) delivered as CSV extracts.
- **Data Governance**: Address data quality challenges and implement cleansing procedures before loading to analytical layers.
- **Unified Model**: Merge multiple sources into a cohesive, intuitive data structure optimized for query performance.
- **Implementation Scope**: Current state implementation only; historical data tracking is out of scope.
- **Knowledge Transfer**: Create comprehensive documentation of the data model for business users and technical teams.

---

### Business Intelligence Layer (Analytics Focus)

#### Goal
Create SQL-based analytical solutions that provide deep visibility into:
- **Customer Analytics**
- **Product Metrics**
- **Revenue Patterns**

These capabilities provide stakeholders with critical business KPIs to support data-driven decisions.  

Additional specifications available in [docs/requirements.md](docs/requirements.md).

## 📂 Project Organization
```
data-warehouse-solution/
│
├── datasets/                           # Source data files (ERP and CRM extracts)
│
├── docs/                               # Technical documentation and design artifacts
│   ├── etl.drawio                      # ETL patterns and methodologies diagram
│   ├── data_architecture.drawio        # System architecture visual
│   ├── data_catalog.md                 # Data dictionary with field definitions
│   ├── data_flow.drawio                # End-to-end data flow visualization
│   ├── data_models.drawio              # Dimensional model diagrams (star schema)
│   ├── naming-conventions.md           # Standardized naming patterns for database objects
│
├── scripts/                            # SQL implementation scripts
│   ├── bronze/                         # Raw data ingestion scripts
│   ├── silver/                         # Data transformation and quality scripts
│   ├── gold/                           # Dimensional model creation scripts
│
├── tests/                              # Quality assurance and validation scripts
│
├── README.md                           # Repository documentation (this file)
├── LICENSE                             # Open source license details
├── .gitignore                          # Git exclusion patterns
└── requirements.txt                    # Project dependencies
```
---

## 🛡️ Licensing

This repository is available under the [MIT License](LICENSE). Feel free to use, adapt, and distribute with appropriate credit.

---
made with love <3 by Madmax
