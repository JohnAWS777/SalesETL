# Fabric_ETL_Sales
This project will create an ETL from scratch using a Lakehouse, a pipeline, and notebooks, based on the following architecture:  
<img width="1037" height="572" alt="image" src="https://github.com/user-attachments/assets/d2cd584b-3ebb-4769-b292-e94c26d71908" />
The ETL works using the following pipeline: 
<img width="1037" height="572" alt="image" src="https://github.com/user-attachments/assets/353d5ea2-4774-4201-b308-cd02419b5989" />


---
## 🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from an Azure SQL Database into a folder in a Lakehouse.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

---
## 📖 Project Overview

This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers.
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting**: Creating a semantic model which can be used to design reports and dashboards for actionable insights.

🎯 This repository aims to showcase expertise in:
- SQL Development
- Data Architect
- Data Engineering  
- ETL Pipeline Developer  
- Data Modeling  
- Data Analytics  

---

## 🛠️ Important Links & Tools:
- **[Microsoft](https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver17&tabs=ssms):** It shows the .bak file AdventureWorksLT2025.bak which is the Azure SQL used in this project.
- **[DrawIO](https://www.drawio.com/):** Design data architecture, models, flows, and diagrams.
---

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern dimensional model using Microsoft Fabric to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
- **Data Sources**: Import data from Adventureworks provided as an Azure SQL Database.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Transformation**: Build a dimensional model using the tables from the Silver layer.
- **Scope**: Historization of data is required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

### BI: Analytics & Reporting (Data Analysis)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Sales by region**
- **Product Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making. 
## 📂 Repository Structure
```
SalesETL/
│
├── 1.BronceLayer/                      # Explains the bronce layer
│   ├── Flow.md                         # This file shows the processes developed in the Bronce stage
├── 2.SilverLayer/                      # Explains the silver layer
│   ├── Flow.md                           # This file shows the processes developed in the Silver stage
│   ├── Python notebooks                  # These files are referenced in the Flow.md file
├── 3.GoldLayer/                        # Explains the gold layer
│   ├── Flow.md                           # This file shows the processes developed in the Gold stage
│   ├── Python notebooks                  # These files are referenced in the Flow.md file
├── 4.SemanticModel/                    # Explains the semantic model
│   ├── DimensionalModel.md               # This file shows the final semantic model
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
```
---


## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

## 🌟 About Me

Hi there! I'm **John**. I’m a Data professional on a mission to create business solutions!
