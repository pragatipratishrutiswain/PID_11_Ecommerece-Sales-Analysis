# Ecommerece Sales Analysis

## Overview:
As a data analyst at a dynamic e-commerce company, I'm tasked with leveraging our extensive databases to extract insights that drive our business strategies forward. My analysis will inform various departments, from marketing to supply chain, providing them with actionable data to optimize our operations, enhance customer satisfaction, and boost our sales performance. This case study simulates real-world tasks I will encounter and requires me to apply my SQL skills to solve practical business problems.

## Business Context:
My work will directly impact the following business verticals:

- **Customer Insights:** Understanding our customer base to tailor marketing strategies.
- **Product Analysis:** Evaluating product performance to inform stock and sales strategies.
- **Sales Optimization:** Analyzing sales data to identify trends, opportunities, and areas for improvement.
- **Inventory Management:** Managing stock levels to ensure product availability while minimizing excess inventory.

## Dataset Details: 
- **Customers Dataset:** customer_id, name, and location
- **Products Dataset:** product_id, name, category, and price.
- **Orders Dataset:** order_id, order_date, customer_id, and total_amount.
- **OrderDetails Dataset:** order_id, product_id, quantity, and price_per_unit.

# ANALYSIS
## Import / Get Data From:
CSV File
## Tools :
1- Power BI<br>
2- Power Query (Merged Tables to denormalize into a single Fact Table)
## KPI Measures:
- **Total Revenue** - Sum of (quantity * price_per_unit), aggregated over time periods.
- **Average Order Value (AOV)** - Total revenue divided by the count of distinct order_id from Orders.
- **Total Orders** - Count of distinct order_id from Orders, often trended daily/weekly/monthly.
- **Total Product Types** - Varieties of products available.
- **Average Quantity per Order** - Average of quantity per order_id.
- **Repeate Purchase Rate** - Proportion of customers with repeat orders (multiple order_id per customer_id) within a cohort period.
