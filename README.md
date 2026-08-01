# 🚀 AdventureWorks Azure Data Engineering Project

## 📌 Project Overview

This project demonstrates an end-to-end Azure Data Engineering pipeline built using the AdventureWorks dataset. The pipeline ingests raw data, stores it in Azure Data Lake Storage Gen2, processes it using Azure Databricks with PySpark, applies Bronze, Silver, and Gold transformations, and visualizes business insights through interactive Power BI dashboards.

---

## 🛠️ Tech Stack

* Azure Data Factory (ADF)
* Azure Data Lake Storage Gen2 (ADLS Gen2)
* Azure Databricks
* PySpark
* Delta Lake
* Power BI
* SQL
* GitHub

---

## 📊 Architecture

```
AdventureWorks Dataset
        │
        ▼
Azure Data Factory
        │
        ▼
Azure Data Lake Storage Gen2
(Bronze Layer)
        │
        ▼
Azure Databricks (PySpark)
(Silver Layer)
        │
        ▼
Gold Layer (Business Tables)
        │
        ▼
Power BI Dashboard
```

---

## 🔄 Data Pipeline

* Data ingestion using Azure Data Factory.
* Raw data stored in the Bronze layer.
* Data cleaning and transformation using PySpark in Databricks.
* Business-ready tables created in the Gold layer.
* Interactive dashboards created in Power BI.

---

## 📂 Project Structure

```
AdventureWorks-Azure-Data-Engineering/
│
├── README.md
├── Architecture/
├── Databricks_Notebooks/
├── PowerBI_Dashboard/
└── Dashboard_Screenshots/
```

---

## 📈 Power BI Dashboard

### Page 1 – Sales Overview

* Total Sales
* Total Quantity
* Total Profit
* Total Cost
* Sales by Category
* Sales by Region
* Sales by Product
* Sales Trend by Order Date
* Region, Category, and Order Date slicers

### Page 2 – Product Analysis

* Sales by Brand
* Sales by Category
* Sales by Product
* Product Details Table

---

## 💡 Skills Demonstrated

* Data Ingestion
* Data Transformation
* ETL Pipeline Development
* Azure Data Lake Storage
* PySpark Programming
* Delta Lake
* Data Modeling
* Power BI Dashboard Development
* Data Visualization

---

## 📷 Screenshots

* Architecture Diagram
* Power BI Dashboard – Page 1
* Power BI Dashboard – Page 2

---

## 👨‍💻 Author

**Purvam Nayak**

Aspiring Azure Data Engineer
