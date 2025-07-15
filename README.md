
# 🍕 Project: Pizza Sales Analysis


## 📚 Table of Contents
- [Problem Statement](#problem-statement)
- [KPI’s Requirement](#kpis-requirement)
- [Charts Requirement](#charts-requirement)
- [Data Analysis using MySQL](#data-analysis-using-mysql)
- [Dashboard using Tableau](#dashboard-using-tableau)
- [Key Insights](#key-insights)
- [Tools and Technologies](#tools-and-technologies)
- [References](#references)

---

## 🧠 Problem Statement

The restaurant had over a year of sales data but lacked clarity on how to use it to optimize business decisions. The objective of this project is to analyze the pizza sales data to identify performance metrics, trends, and improvement opportunities across sales, operations, and customer behavior.

---

## 📌 KPI’s Requirement

We aimed to calculate the following KPIs using SQL:

1. **Total Revenue** – Total sum of all pizza sales.
2. **Average Order Value** – Revenue per order.
3. **Total Pizzas Sold** – Total quantity of pizzas sold.
4. **Total Orders** – Unique count of orders placed.
5. **Average Pizzas Per Order** – Total pizzas divided by total orders.

---

## 📊 Charts Requirement

We identified the following charts to visualize and analyze performance:

1. **Hourly Trend for Total Pizzas Sold** – Identify busiest times.
2. **Weekly Trend for Total Orders** – Seasonal and weekly insights.
3. **% Sales by Pizza Category** – Visualize category-wise revenue.
4. **% Sales by Pizza Size** – Understand customer size preferences.
5. **Total Pizzas Sold by Category** – Funnel chart for quantity by type.
6. **Top 5 Pizzas (Revenue, Quantity, Orders)** – Best performers.
7. **Bottom 5 Pizzas (Revenue, Quantity, Orders)** – Worst performers.

---

## 💻 Data Analysis using MySQL

Using MySQL, I wrote SQL queries to calculate the KPIs and prepare the data for visualization.
📊 SQL Summary: Key Metrics & Insights
💰 Total Revenue Generated: ₹817,860 from all pizza sales.
🛍️ Total Orders: 4,869 unique customer orders.
🍕 Total Pizzas Sold: 49,574 pizzas in total.
💸 Average Order Value (AOV): ₹38.31 per order.
📦 Average Pizzas per Order: Around 2.28 pizzas per order.

⏰ Sales Trends
Hourly Trend: Sales peak during 12 PM–1 PM and 6 PM–8 PM, suggesting lunch and dinner rushes.
Weekly Trend: Highest order volumes appear during the last week of December, indicating seasonal surges.

🧁 Category & Size Analysis
By Category:
Classic pizzas generated the highest revenue.
Veggie pizzas contributed the least.

By Size:

Large pizzas were the most preferred.
Small pizzas saw the lowest sales and revenue share.

🥇 Top Performers
Top 5 Pizzas by Revenue: The best-selling pizzas contributed significantly to overall income.
Top 5 Pizzas by Quantity Sold: These pizzas were customer favorites in terms of volume.
Top 5 Pizzas by Total Orders: These had the highest repeat and unique order counts.

📉 Low Performers
Bottom 5 Pizzas by Revenue, Quantity, and Orders:
These underperformed across all KPIs and could be candidates for promotions or menu re-evaluation.

📈 Dashboard using Tableau
A pizza-themed interactive dashboard was created using Tableau including:

KPI Cards
Total Revenue SUM([order id])
Total Orders COUNTD([order id])
Average Order Value [total revenue] / [total orders]
Total Pizzas Sold SUM([quantity])
Average Pizzas Per Order [total pizzas sold] / [total orders]
![](https://github.com/SREEJITA1904/PIZZA-SALES-ANALYSIS/raw/main/KPI's.png)
Hourly & Weekly Trends
Sales Distribution (Size & Category)
Best vs Worst Sellers
![Dashboard 1](dashboard_preview.png)
![Dashboard 2](dashboard_preview.png)

✨ Key Insights
![KEY](dashboard_preview.png)

🧰 Tools and Technologies
Tool	Purpose
MySQL 8.0.36	Data querying and analysis
Excel 2021	Pre-processing, CSV cleanup
Tableau 2024	Data visualization & dashboarding
Canva	Theme design for dashboard/report

🔗 References
YouTube: @datatutorials1
Topmate: Data Tutorials

![Dasboard use]()
