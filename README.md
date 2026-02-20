📊 Power BI Retail Sales Dashboard 

📌 Project Overview

This project presents an interactive Retail Sales Performance Dashboard built using Microsoft Power BI.

The dashboard transforms raw sales data into a structured analytical model using a Star Schema and provides actionable business insights through dynamic KPIs and interactive visualizations.

The goal was to enable data-driven decision-making by analyzing sales trends, profitability, product performance, and regional insights.


🎯 Business Objective

The dashboard helps stakeholders:

Monitor overall sales and profit performance

Identify top-performing categories and products

Analyze monthly sales trends

Compare regional sales performance

Evaluate profit margin and discount impact


🏗 Data Model (Star Schema)

The data was structured into a Star Schema model:


📌 Fact Table

fact_sales

Sales

Profit

Discount

Order Date

Foreign Keys


📌 Dimension Tables

dim_customer

dim_product

dim_date

dim_location

Each dimension table has a one-to-many relationship with the fact table to ensure efficient filtering and accurate aggregation.

The Date table was marked as a Date Table to enable time intelligence calculations.


📊 Key KPIs

✅ Total Sales

✅ Total Profit

✅ Profit Margin (%)

✅ Average Discount (%)

✅ Sales by Category

✅ Sales by Region

✅ Monthly Sales Trend

All KPIs update dynamically using slicers and filters.


🛠 Tools & Skills Used

Power BI Desktop

Power Query (Data Cleaning & Transformation)

Star Schema Data Modeling

Relationship Management

DAX Calculations

Time Intelligence Functions

Interactive Dashboard Design


📈 Sample DAX Measures
Total Sales = SUM(fact_sales[Sales])

Total Profit = SUM(fact_sales[Profit])

Profit Margin % = 
DIVIDE([Total Profit], [Total Sales], 0)

Average Discount % = 
AVERAGE(fact_sales[Discount])

📷 Dashboard Features
Interactive Slicers (Year, Category, Region)

KPI Cards with Dynamic Updates

Sales Trend Line Chart

Category-wise Sales Comparison

Regional Profit Analysis

Clean and Professional Layout Design


🔄 Data Preparation Steps

Removed duplicates

Handled missing values

Corrected data types

Created calculated columns

Built relationships between fact and dimension tables


🚀 Project Outcome

Successfully designed and implemented a fully interactive Power BI dashboard that enables:

Clear performance monitoring

Profitability analysis

Trend identification

Business-focused insights

This project demonstrates strong skills in data modeling, DAX, and dashboard design.

👩‍💻 About Me

Faesa
Mathematics Graduate
Skilled in Excel,statistics, SQL, Power BI, and Tableau

This project reflects my ability to transform raw data into meaningful business insights using modern BI tools.
