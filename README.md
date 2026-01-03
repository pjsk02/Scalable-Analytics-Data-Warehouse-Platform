# 📊 Scalable Analytics & Data Warehouse Platform

### Dashboard Link  
https://app.powerbi.com/groups/me/reports/2b0f49c5-e2d0-4b6c-afe1-128b4303dc6f/7638e95db92838a5585c?experience=power-bi

---

## 📌 Summary  

🚀 **End-to-End Data Engineering & Analytics Platform** built to process large-scale, real-world structured datasets and deliver KPI-driven insights.

This project demonstrates:
- **Data Engineering**: Cloud ETL pipelines, warehouse design, dimensional modeling  
- **Data Analytics**: Data profiling, cleansing, normalization, scoring, and metric derivation  
- **Business Intelligence**: Interactive dashboards and executive reporting using Power BI  

The solution is intentionally **domain-agnostic** and reusable across industries such as technology, operations, compliance, and business analytics.

---

## 📂 Datasets  

- **Dataset A**: ~300K records with mixed categorical and numerical attributes  
- **Dataset B**: ~80K records with wide schemas and semi-structured fields  

These datasets simulate common real-world challenges such as inconsistent schemas, nested fields, and data quality issues.

---

## 🛠️ Tech Stack  

| Category               | Tools Used |
|------------------------|------------|
| Data Profiling         | YData, Alteryx |
| ETL & Pipelines        | Azure Data Factory, Snowflake, Databricks, SQL |
| Data Modeling          | ER/Studio – Dimensional (Star Schema) |
| Visualization          | Power BI – KPI Dashboards, Interactive Filters |
| Scripting & Cleaning   | Python, Regex, SQL |

---

## 🧼 Data Engineering Process  

### 🧱 Medallion Architecture  

Implemented a **Bronze → Silver → Gold** architecture using Snowflake, Databricks, and Azure Data Factory.

- **Bronze**: Raw data ingestion  
- **Silver**: Data cleaning, parsing, and standardization  
- **Gold**: Analytics-ready dimensional models optimized for BI and reporting  

---

### 🔄 ETL Highlights  

- Cleaned and transformed wide, high-column datasets using Alteryx workflows  
- Parsed nested and delimited fields into normalized structures  
- Derived standardized outcome metrics and categorical classifications  
- Applied regex-based transformations to improve schema consistency  
- Converted denormalized inputs into analytics-ready relational formats  

---

## 🧾 Data Warehouse Design  

🧠 **Grain**: One row per event per entity per date  

### 📌 Dimension Tables  
- DIM_LOCATION  
- DIM_ENTITY  
- DIM_EVENT  
- DIM_RESULT  
- DIM_CATEGORY  

### 📌 Fact Table  
- FACT_EVENTS – captures measurable outcomes and joins all dimension keys  

All tables are orchestrated and loaded via Azure Data Factory pipelines.

---

## 📈 Key Skills Demonstrated  

- End-to-end cloud data pipeline development  
- Dimensional modeling and analytics engineering  
- Advanced data cleansing and normalization  
- ETL orchestration with Azure Data Factory  
- KPI design and interactive BI reporting  

---

## 🎯 What This Project Demonstrates  

- Ability to transform complex, messy datasets into analytics-ready assets  
- Strong understanding of cloud data platforms and BI workflows  
- End-to-end ownership from ingestion to executive dashboards  
- Scalable design principles applicable across multiple industries  

---

## 🧩 Dimensional Model  

![DimensionalModel](https://github.com/user-attachments/assets/76a07d40-1e9f-4a73-a0d6-7d53d939a6af)

---

## 🔄 Data Pipeline (Azure Data Factory)  

![DataPipeline](https://github.com/user-attachments/assets/46c88787-82a2-4c80-9733-c79720b0c662)

---

## 📊 Power BI Dashboard  

The BI layer includes interactive dashboards with:
- Time-based trend analysis  
- Location and category-level insights  
- Risk and outcome distribution metrics  
- Geographic and segment-based heatmaps  
- Executive summary KPIs and drill-down views  

![Dashboard_Home](https://github.com/user-attachments/assets/1d825e36-3544-4a53-a531-8ddf22571ca4)
![Dashboard_P1](https://github.com/user-attachments/assets/f55ef30e-8c44-4434-b2cc-542f4944fbda)
![Dashboard_P2](https://github.com/user-attachments/assets/501f3ee3-7f76-40d9-bf45-9904b08b136c)
![Dashboard_P3](https://github.com/user-attachments/assets/0a8ef768-42df-4bc2-bbb3-688e9c237af6)
![Dashboard_P4](https://github.com/user-attachments/assets/ee406600-70b2-43e6-81b6-1bea6d1400bc)
![Dashboard_P5](https://github.com/user-attachments/assets/c776c17f-df97-4c22-b42c-9c39470c362d)
![Dashboard_P6](https://github.com/user-attachments/assets/abaed663-822d-4b25-972b-93ff0895fcb8)
![Dashboard_P7](https://github.com/user-attachments/assets/287fc845-5159-42d4-bd43-807256a8c037)

---

Feel free to fork, explore, or adapt this project.  
📬 Let’s connect on [LinkedIn](https://www.linkedin.com/in/je-pulipati/) — open to Data Engineering, Analytics, and BI roles.
