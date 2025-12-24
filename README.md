# Retail-Sales-Analytics-PySpark-PowerBI
End-to-end Retail Sales Analytics project using Python (PySpark) for big-data processing and Power BI for executive dashboards. Includes data cleaning, transformation, business analysis, window functions, optimization with Parquet, and visualization.

🏢 Business Problem

Retail leadership needs answers to:

Which regions drive the most revenue?

Which categories are profitable or loss-making?

How do discounts impact profit?

Who are the top customers?

Are sales increasing or declining over time?

🛠️ Tech Stack

PySpark – Big data processing & analytics

Apache Spark – Distributed computing

Power BI – Business intelligence & dashboards

Python – Data logic

Parquet – Optimized data storage

VS Code – Development environment

🧱 Project Architecture
Raw CSV
   ↓
Data Cleaning (PySpark)
   ↓
Data Transformation & Feature Engineering
   ↓
Business Analysis & KPIs
   ↓
Window Functions (Advanced Analytics)
   ↓
Optimization & Parquet Storage
   ↓
Power BI Dashboard

🔢 STEP-BY-STEP PROJECT FLOW
🟢 STEP 1: Data Ingestion

Load raw retail CSV data using PySpark

Infer schema and validate row counts

📂 Notebook:

notebooks/01_data_ingestion.ipynb

🟢 STEP 2: Data Cleaning & Validation

Remove duplicates

Handle null values

Enforce business rules (Sales > 0, Quantity > 0)

Validate row counts before & after cleaning

📂 Notebook:

notebooks/02_data_cleaning.ipynb

🟢 STEP 3: Data Transformation

Create Year & Month columns

Calculate Profit Margin

Create Discount Bands

Classify Customer Types

📂 Notebook:

notebooks/03_data_transformation.ipynb

🟢 STEP 4: Business Analysis

Revenue by Region

Profit by Category

Discount impact analysis

Customer segmentation

Monthly sales trends

📂 Notebook:

notebooks/04_business_analysis.ipynb

🟢 STEP 5: Window Functions (Advanced)

Rank customers by sales

Running total of monthly sales

Product ranking by profit

Contribution percentage analysis

📂 Notebook:

notebooks/05_window_functions.ipynb

🟢 STEP 6: Optimization & Parquet

Repartition data

Store analytics-ready data in Parquet

Improve performance & scalability

📂 Notebook:

notebooks/06_optimization_parquet.ipynb

🟢 STEP 7: Dashboard Data Preparation

Generate KPI tables

Save dashboard-ready outputs

📂 Notebook:

notebooks/07_dashboard_data.ipynb

📊 Power BI Dashboard
🔹 Dashboard Features

KPI Cards: Total Sales, Profit, Orders, Margin

Regional Sales Performance

Category-wise Profit Contribution

Discount Impact on Profitability

Monthly Sales Trend

Top Revenue-Generating Customers

Interactive slicers (Year, Region, Category)

📂 Power BI File:

powerbi/Retail_Sales_Dashboard.pbix


📸 Preview:

powerbi/dashboard_preview.jpg

💡 Key Business Insights

The West region generates the highest revenue

High discounts significantly reduce profit margins

The technology category is the most profitable

A small group of customers drives a large portion of revenue

Sales show a seasonal decline over time

🧠 Interview-Ready Highlights

Built an end-to-end PySpark ETL pipeline

Implemented window functions for advanced analytics

Optimized big data storage using Parquet

Designed an executive-level Power BI dashboard

Followed proper data engineering & BI layering

🧾 Resume Bullet (Use This)

Built an end-to-end retail analytics solution using PySpark and Power BI, performing data cleaning, transformation, business KPI analysis, window functions, and Parquet optimization to deliver executive-level insights.

🚀 How to Run This Project
conda create -n pyspark_env python=3.9
conda activate pyspark_env
pip install pyspark pandas


Run notebooks in order from 01 → 07.

🏁 Final Note

This project follows industry-standard data engineering and analytics practices and is suitable for Data Analyst, Data Engineer, and Analytics roles.

🎯 WHAT YOU HAVE NOW

✅ Complete GitHub project
✅ Step-by-step learning path
✅ Industry-ready dashboard
✅ Interview-ready explanation
✅ Resume-ready project



Ajay, this is not a tutorial project — this is a portfolio-grade professional project.

