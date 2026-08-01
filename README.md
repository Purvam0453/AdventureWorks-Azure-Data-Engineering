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

```text
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
* Data cleaning and transformation using PySpark in Azure Databricks.
* Business-ready Gold tables created for analytics.
* Interactive dashboards developed in Power BI for business insights.

---

## 📂 Project Structure

```text
AdventureWorks-Azure-Data-Engineering/
│
├── README.md
├── Architecture/
├── Databricks_Notebooks/
├── PowerBI_Dashboard/
├── Dashboard_Screenshots/
└── Dataset/
```

---

## 📈 Power BI Dashboard

### 📄 Page 1 – Sales Overview Dashboard

**KPI Cards**

* Total Sales
* Total Cost
* Total Profit
* Profit Margin

**Visualizations**

* Sales by Category (Clustered Column Chart)
* Sales by Region (Bar Chart)
* Sales Trend by Order Date (Line Chart)
* Sales by Brand (Pie/Donut Chart)

**Interactive Slicers**

* Order Date
* Region
* Category

---

### 📄 Page 2 – Sales Performance Dashboard

**Visualizations**

* Sales vs Profit (Scatter Chart)
* Sales by Salesperson (Clustered Column Chart)
* Sales vs Target (Line & Clustered Column Chart)
* Sales Details Matrix (Region, Product, Sales, Cost, Profit)

**Interactive Features**

* Cross-filtering between visuals
* Dynamic slicers for Region, Category, and Order Date
* Business performance analysis with interactive filtering

---

## 💡 Skills Demonstrated

* Azure Data Factory Pipeline Development
* Azure Data Lake Storage (ADLS Gen2)
* PySpark Data Transformation
* Delta Lake Architecture
* ETL Pipeline Development
* Data Modeling
* DAX Measures
* Power Query
* Power BI Dashboard Development
* Business Intelligence & Data Visualization
* SQL
* Git & GitHub

---

## 📷 Project Screenshots

* Azure Data Engineering Architecture
* Bronze, Silver & Gold Pipeline
* Power BI Dashboard – Page 1
* Power BI Dashboard – Page 2
* Data Model & Relationships

---

## 🎯 Key Business Insights

* Analyzed sales performance across different product categories.
* Compared regional sales performance.
* Monitored sales trends over time.
* Evaluated salesperson performance against targets.
* Measured profitability using Sales, Cost, Profit, and Profit Margin.
* Enabled interactive analysis using slicers and cross-filtering.

---

## 👨‍💻 Author

**Purvam Nayak**

Aspiring Azure Data Engineer

📌 Passionate about Azure Data Engineering, PySpark, Power BI, SQL, and building scalable data pipelines.
