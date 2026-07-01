# 🇧🇷 Brazilian E-Commerce Analytics Dashboard

<p align="center">

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-success)
![Star Schema](https://img.shields.io/badge/Data%20Model-Star%20Schema-orange)

</p>

> Executive Power BI dashboard built using the Brazilian Olist E-Commerce dataset.

## 📑 Table of Contents
- Project Overview
- Business Objectives
- Dataset
- Tech Stack
- Dashboard Pages
- Data Model
- DAX Measures
- Workflow
- Folder Structure
- Skills

---

# 🚀 Project Overview

```text
Raw CSV
   │
   ▼
Power Query
   │
   ▼
Star Schema
   │
   ▼
DAX Measures
   │
   ▼
Interactive Dashboards
```

# 🎯 Business Objectives

- Monitor sales
- Analyze customers
- Evaluate sellers
- Improve operations

# 🗂 Dataset

9 CSV files from the Brazilian Olist E-Commerce dataset.

# 🛠 Tech Stack

- Power BI
- Power Query
- DAX
- Data Modeling

# 📊 Dashboard Pages

## Executive Dashboard

![Executive](Screenshots/Executive_Dashboard.png)

## Customer & Product Analysis

![Customer](Screenshots/Customer_and_Product_Analysis.png)

## Operations & Customer Satisfaction

![Operations](Screenshots/Opertions_and_Customer_Satisfaction.png)

# 🏗 Data Model

## Initial

![Initial](Screenshots/Initial_Model_View.png)

## Final

![Relationships](Screenshots/Model_View_Relationships.png)

```text
               DimDate
                  │
DimCustomers─DimOrders─FactPayments
                  │
            FactOrderItems
             │         │
      DimProducts  DimSellers
                  │
             FactReviews
```

# 📈 Key DAX Measures

- Total Revenue
- Total Orders
- Total Customers
- Total Products
- Total Sellers
- Average Order Value
- Average Revenue Per Customer
- Average Review Score
- Average Freight
- Average Installments

# 🔄 Workflow

```text
Import → Clean → Model → DAX → Dashboard → Insights
```

# 📁 Folder Structure

```text
PR3
├── Assets
├── Datasets
├── Screenshots
├── Brazilian_E-Commerce_Public_Dashboard.pbix
└── README.md
```

# 💼 Skills Demonstrated

- Power BI
- Power Query
- DAX
- Star Schema
- Dashboard Design
- Business Intelligence

# 👨‍💻 Author

**Dushyant V**

⭐ If you like this project, consider starring the repository.
