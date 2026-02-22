# Data Warehouse and Analytics Project

**BY** Samiha Jahan Ema  

---

## 📌 Overview

This repository contains a complete end-to-end Data Warehouse and Analytics project.  
The project demonstrates how to design and implement a modern data warehouse using SQL Server, following industry best practices.

The workflow covers data ingestion, transformation, modeling, and analytical reporting.

---

## 🏗️ Architecture

The data warehouse follows the Medallion Architecture pattern with three layers:

### 1. Bronze Layer
- Stores raw data from source systems (ERP and CRM)
- Data loaded from CSV files into SQL Server
- No transformation applied

### 2. Silver Layer
- Data cleaning and validation
- Standardization and normalization
- Prepared for analytical modeling

### 3. Gold Layer
- Business-ready data
- Star schema design (Fact and Dimension tables)
- Optimized for reporting and analytics

---

## 🔄 ETL Process

The ETL process includes:

- Extracting data from CSV files
- Transforming data (cleaning, validation, formatting)
- Loading processed data into structured warehouse tables

---

## 📊 Analytics & Reporting

SQL queries are developed to generate insights related to:

- Customer behavior
- Product performance
- Sales trends

These insights support data-driven decision-making.

---

## 🛠️ Technologies Used

- SQL Server Express
- SQL Server Management Studio (SSMS)
- Git & GitHub
- Draw.io
- CSV datasets

---

## 📂 Repository Structure

```
data-warehouse-project/
│
├── datasets/          # Source data (CSV files)
├── docs/              # Documentation and diagrams
├── scripts/           # SQL scripts (Bronze, Silver, Gold layers)
├── tests/             # Testing and validation scripts
├── README.md
├── LICENSE
└── requirements.txt
```

---

## ▶️ How to Run the Project

1. Install SQL Server Express.
2. Install SQL Server Management Studio (SSMS).
3. Import datasets from the `datasets/` folder.
4. Execute SQL scripts in order:
   - Bronze layer
   - Silver layer
   - Gold layer
5. Run analytical queries for reporting.

---

## 📄 License

This project is licensed under the MIT License.
You are free to use, modify, and distribute this project with proper attribution.

---

## 👩‍💻 About Me

I am Samiha Jahan Ema,  
Aspiring Data Engineer and Data Analyst  
Focused on building practical, real-world data projects.
