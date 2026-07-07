# Bank-Marketing-Analytics
# 🏦 Bank Marketing Analytics using Microsoft Fabric

## 📌 Project Overview

This is an end-to-end Data Engineering project built using **Microsoft Fabric**. The project follows the **Medallion Architecture (Bronze, Silver, and Gold layers)** to transform raw banking data into business-ready insights.

The final data is used to build interactive **Power BI dashboards** that help analyze customer information and marketing campaign performance.

---

# 🛠️ Technologies Used

- Microsoft Fabric
- PySpark
- Delta Lake
- Lakehouse
- SQL
- Microsoft Fabric Pipeline
- Power BI
- GitHub

---

# 📂 Project Architecture

```
Raw CSV Data
      │
      ▼
Bronze Layer
(Raw Data)
      │
      ▼
Silver Layer
(Data Cleaning & Transformation)
      │
      ▼
Gold Layer
(Business Ready Tables)
      │
      ▼
Fabric Pipeline
      │
      ▼
Power BI Semantic Model
      │
      ▼
Power BI Dashboard
```

---

# 📁 Project Structure

```
Bank-Marketing-Analytics
│
├── Architecture
├── Notebooks
│   ├── Bronze
│   ├── Silver
│   └── Gold
├── Pipeline
├── PowerBI
└── README.md
```

---

# 🥉 Bronze Layer

The Bronze layer stores the raw banking dataset without making any changes.

### Tasks Performed

- Loaded CSV data into the Lakehouse
- Created Bronze Delta table
- Verified schema and row count

---

# 🥈 Silver Layer

The Silver layer cleans and transforms the data.

### Tasks Performed

- Removed null values
- Standardized data
- Created new business columns
- Prepared data for analysis

---

# 🥇 Gold Layer

The Gold layer contains business-ready tables used for reporting.

### Gold Tables

- Gold Customer Overview
- Gold Campaign Performance
- Gold Risk & Revenue Insights

---

# 🔄 ETL Pipeline

A Microsoft Fabric Pipeline was created to automate the ETL process.

Pipeline Flow:

```
Bronze Notebook
      │
      ▼
Silver Notebook
      │
      ▼
Gold Notebook
```

---

# 📊 Power BI Reports

## Report 1: Customer Analytics

### Page 1

- Total Customers
- Average Income
- Average Credit Score
- Customer Segment
- Region-wise Customers
- Age Group Distribution

### Page 2

- Income Band Distribution
- Risk Level vs Credit Score
- Loan Status Breakdown
- Top 10 High-Income Customers

---

## Report 2: Marketing Performance

### Page 1

- Success Rate KPI
- Channel Performance
- Contact Method Performance
- Region-wise Conversion Rate

### Page 2

- Job-wise Campaign Success
- Education vs Conversion
- Duration vs Success
- Region & Channel Heatmap

---

# 📈 Key Learnings

Through this project, I learned:

- Medallion Architecture
- Microsoft Fabric Lakehouse
- PySpark Data Transformation
- Delta Lake Tables
- Data Pipelines
- Semantic Models
- Power BI Dashboard Development
- GitHub Project Documentation

---

# 👨‍💻 About Me

I am a beginner Data Engineer passionate about building end-to-end data projects using Microsoft Fabric, PySpark, SQL, and Power BI. This project helped me understand how raw data is transformed into meaningful business insights using modern data engineering practices.
