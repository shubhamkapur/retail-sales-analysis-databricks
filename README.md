# Retail Sales Analysis using Azure Databricks & Spark SQL

## Project Overview
This project analyzes multi-year retail sales data to uncover revenue trends, store efficiency, and product performance. The analysis was performed using Azure Databricks and Spark SQL to simulate large-scale data processing and analytics. Dashboards created in Databricks SQL for interactive analysis

---

## Objectives
- Clean and integrate raw sales and store datasets
- Analyze revenue trends using Year-on-Year (YoY) growth
- Measure store efficiency using Sales per Square Foot
- Identify top-performing products, stores, and regions
- Evaluate the relationship between store size and revenue

---

## Dataset Description
The project uses two datasets:
- **sales**: Transaction-level sales data
- **store**: Store metadata including region and store size

The datasets were cleaned and combined using **INNER JOINs** in Spark SQL.

---

## Tools & Technologies
- Azure Databricks
- Spark SQL
- Window Functions (LAG)
- Data Cleaning & Aggregation
- KPI-based Analysis
- Databricks Visualizations

---

## Key Metrics
- Total Revenue
- Year-on-Year (YoY) Revenue Growth
- Sales per Square Foot
- Average Sales by Store Size Bucket
- Product-wise Revenue and Quantity Sold

---

## Key Findings
- Revenue declined in 2021 and recovered in 2022.
- North region generated the highest total revenue.
- West region stores showed the highest efficiency (sales per sq. ft).
- Medium-sized stores outperformed large stores in average revenue.
- High-revenue products are not always the most sold by quantity.

---

## Key Visualizations

### Year-on-Year Revenue
![YoY Revenue](assets/visual/YoY_revenue.png)

### Top 10 Products by Revenue
![Top Products](assets/visual/top10_max_revenue_products.png)

### Sales per Square Foot by Region
![Sales per Sq Ft](assets/visual/sales_per_sq_ft_grpby_store_region.png)

---

## Conclusion
This project demonstrates how analytical KPIs and scalable data tools can be used to extract actionable insights from retail datasets, supporting data-driven decision-making.

---
