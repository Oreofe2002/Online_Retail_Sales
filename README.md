Online Retail Sales Analysis & Customer Segmentation
📌 Project Overview

This project analyzes transactional data from an online retail store to uncover:

Revenue performance trends

Top-selling products

Geographic sales distribution

Customer purchasing behavior

Customer segmentation using RFM Analysis

The goal is to transform raw transactional data into meaningful business insights and an interactive Tableau dashboard for executive-level decision-making.

📊 Business Objectives

Identify total revenue and monthly revenue trends

Determine top-performing products

Analyze revenue contribution by country

Distinguish repeat vs one-time buyers

Segment customers using RFM analysis

Provide actionable marketing insights

📂 Dataset Description

The dataset contains transactional retail data including:

Invoice – Order ID

StockCode – Product Code

Description – Product Name

Quantity – Number of units purchased

InvoiceDate – Date and time of purchase

UnitPrice – Price per unit

CustomerID – Unique customer identifier

Country – Customer location

🧹 Data Cleaning Process

The following preprocessing steps were applied:

Converted InvoiceDate to datetime format

Removed cancelled invoices (Invoice starting with "C")

Removed negative quantities (returned items)

Created Revenue = Quantity × UnitPrice

Handled missing Description and CustomerID values

Removed invalid transactions

💰 Key Metrics Calculated

Total Revenue

Monthly Revenue Trends

Revenue by Country

Top 5 Products by Revenue

Repeat vs One-Time Customers

👥 Customer Segmentation (RFM Analysis)

RFM (Recency, Frequency, Monetary) analysis was used to segment customers.

RFM Metrics

Recency → Days since last purchase

Frequency → Number of unique invoices

Monetary → Total revenue generated

Customers were scored using quintiles (1–5 scale).

Customer Segments

 Lost Customers

 Loyal Customers

 Potential Loyalists

 At Risk

 Lost Customers

Segmentation helps identify high-value customers and churn risks.

📈 Dashboard Overview (Tableau)

The interactive Tableau dashboard includes:

KPI Cards (Total Revenue, Orders, Customers)

Monthly Revenue Trend (Line Chart)

Top Products (Ranked List)

Revenue by Country

Customer Status (Active vs Inactive)

RFM Customer Segmentation

The dashboard is designed using a clean green theme to reflect business growth and financial health.

🛠️ Tools & Technologies Used

Python (Pandas, NumPy) – Data cleaning & RFM analysis

Tableau – Interactive dashboard visualization

GitHub – Version control & project documentation

📊 Business Insights

Revenue is highly concentrated in a few top-performing products

A significant portion of revenue comes from repeat customers

Certain countries dominate total revenue contribution

At-risk customers represent a key retention opportunity

🚀 How to Run This Project

Clone the repository

Open the Jupyter notebook

Run data cleaning and RFM segmentation scripts

Open the Tableau workbook

Connect to cleaned dataset and RFM file

📌 Future Improvements

Add predictive churn modeling

Implement cohort analysis

Build marketing campaign targeting recommendations

Deploy dashboard to Tableau Public

👤 Author

Posun Oreofe
Data Analyst | Business Intelligence Enthusiast
