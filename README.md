# 🏬 Retail Data Warehouse Project (SQL Server + Power BI)

An end-to-end Data Warehouse project built using SQL Server and Power BI, based on a realistic retail business scenario. This project implements a layered architecture (Staging → Clean → Business) and covers data ingestion, transformation, and reporting over 10,000+ sales records.

---

## 🚀 Project Objectives

- Build a real-world Data Warehouse using SQL Server
- Design facts and dimensions to support analytics
- Implement ETL logic from raw source to reporting-ready tables
- Create a Power BI dashboard for business insights

---

## 🧱 Architecture

# Retail-Sales-Data-Warehouse
 End-to-end Data Warehouse project using SQL Server &amp; Power BI, built on a realistic retail dataset with over 10,000 sales records. Includes staging, transformation, reporting layers, and ETL pipelines.

 Source CSV Files
↓
[ Staging Tables ]
↓
[ Cleaned & Transformed Tables ]
↓
[ Business Layer (Facts & Dimensions) ]
↓
[ Power BI Dashboards ]


- **Staging Layer**: Raw import of CSVs
- **Clean Layer**: Deduplicated, validated, and joined data
- **Business Layer**: Fact tables (sales, inventory), Dim tables (customer, product, store)
- **Reporting**: Interactive Power BI dashboard

---

## 📦 Dataset Overview

The project uses synthetic, realistic retail data generated for this use case. All data is stored in `/datasets/` as `.csv` files.

| Table           | Type        | Description                           |
|----------------|-------------|---------------------------------------|
| `customers.csv` | Dimension   | Customer profile and region           |
| `products.csv`  | Dimension   | Product catalog with category & price |
| `stores.csv`    | Dimension   | Store locations and managers          |
| `calendar.csv`  | Dimension   | Date reference table                  |
| `inventory.csv` | Fact        | Daily inventory levels per store      |
| `sales.csv`     | Fact        | Transactions including amount, qty    |

---

## 🛠 Tech Stack

- **SQL Server 2022** – Database & ETL logic
- **SSMS** – Development & query execution
- **Power BI** – Reporting & visualization
- **Git & GitHub** – Version control & collaboration

---

## 📊 Power BI Dashboard

> *Coming Soon* – Screenshots and `.pbix` file will be added here.

Features:
- Sales trend analysis
- Top selling products
- Regional sales performance
- Inventory vs Sales KPIs

---

## 🧠 Key Concepts Covered

- Dimensional modeling (Fact/Dim)
- Data transformation using SQL
- ETL best practices
- Reporting & KPIs
- Time series data handling
- Realistic data warehouse architecture

---

## 🙏 Acknowledgements

This project is inspired by the excellent work of [@DataWithBaraa](https://github.com/DataWithBaraa), whose content helped me understand the layered data warehouse architecture and SQL implementation. I've built a custom dataset and made modifications to create a unique portfolio project.

---

## 📂 Folder Structure

retail-data-warehouse-sql/
│
├── datasets/ 
├── sql/
│ ├── staging/ # Scripts to load raw data
│ ├── transformations/ # Scripts to clean/transform
│ └── reporting/ # Scripts to build fact/dim tables
├── powerbi/ # Power BI reports & screenshots
├── diagrams/ # ERD and flow diagrams
└── README.md # You're here!


