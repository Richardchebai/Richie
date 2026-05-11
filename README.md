🛒 Sales Analysis Dashboard
Analyzing retail sales trends and building KPI dashboards to drive business decisions.
📌 Project Overview
This project explores a retail sales dataset to uncover trends, identify top-performing products, and visualize key performance indicators (KPIs) that help business stakeholders make data-driven decisions. The analysis covers sales by region, product category, time period, and customer segment.
🎯 Objectives
Identify the best and worst performing product categories
Track monthly and quarterly revenue trends
Analyse regional sales performance
Build an interactive KPI dashboard for business reporting
🛠️ Tools & Technologies
�
�
�
�
�
📁 Project Structure
Code
📊 Dataset Overview
Raw Data (data/raw/sales_raw.csv)
45 sales transactions across 2024 with the following columns:
Column
Description
order_id
Unique order identifier
order_date
Date the order was placed
customer_id
Unique customer code
customer_name
Customer full name
product
Product purchased
category
Technology / Furniture / Office Supplies
quantity
Units ordered
unit_price
Price per unit (USD)
region
West / East / North / South
discount
Discount applied (0.00–0.10)
returned
Whether the item was returned (Yes/No)
Cleaned Data (data/cleaned/sales_cleaned.csv)
Processed version with additional engineered columns:
Added Column
Description
total_revenue
quantity × unit_price
net_revenue
total_revenue after discount, returned items = 0
month
Extracted month name
quarter
Q1 / Q2 / Q3 / Q4
year
Transaction year
🔍 Key Findings
Technology products generated the highest revenue, accounting for 38% of total sales
Sales peak in Q4 every year, indicating strong seasonal trends
The West region consistently outperformed all other regions
A small group of top 10 customers contributed to 22% of total revenue
📸 Screenshots
Revenue by Category
�
Monthly Revenue Trend
�
Regional Sales Performance
�
Top Customers by Revenue
�
📌 Note: Run the notebook to auto-generate all charts into the visuals/ folder.
🚀 How to Run
Clone this repository
Bash
Install required libraries
Bash
Open the notebook
Bash
All charts will be saved automatically to the visuals/ folder.
📬 Contact
Richard 0792983387 — LinkedIn https://www.linkedin.com/in/richardkarani · Email richardkarani038@gmail.com 