# 🍕 Pizza Sales Analysis - Power BI Dashboard
This repository contains a Power BI report that provides an in-depth analysis of pizza sales data for a pizzeria. The report is designed to help the pizzeria owners and managers gain valuable insights into their sales performance, popular pizza categories and sizes, busiest times, and best and worst-selling pizza varieties.

# Dataset Overview
This dataset provides detailed information about pizza orders, likely from a pizzeria. Here's a breakdown of the columns:<br>
**pizza_id:** Unique identifier for each distinct pizza variant available for ordering.<br>
**order_id:** Unique identifier for each order placed by a customer.<br>
**pizza_name_id:** Identifier linking to a specific name of the pizza (pizza_name).<br>
**quantity:** The number of units of a specific pizza variant ordered.<br>
**order_date:** Date the order was placed.<br>
**order_time:** Time the order was placed.<br>
**unit_price:** Cost of a single unit of the specific pizza variant.<br>
**total_price:** Aggregated cost of all units of a specific pizza variant in an order (quantity * unit_price).<br>
**pizza_size:** Size of the pizza ordered.<br>
**pizza_category:** Category of the pizza ordered.<br>
**pizza_ingredients:** List of ingredients used in the pizza.<br>
**pizza_name:** The full name of the pizza as it appears on the menu.<br>

# Purpose
The purpose of the Pizza Sales Analysis Dashboard is to provide a comprehensive visual representation of a pizzeria's sales data, enabling stakeholders to identify key performance indicators, analyze trends, pinpoint top and bottom-performing products, and make data-driven decisions to optimize operations and profitability.

# Tools Used
SQL Server Management Studio<br>
SQL<br>
Power BI<br>
Power Query<br>

# Steps to be followed:
1. Imported raw sales data into SQL Server using the Import Task option in SQL Server Management Studio (SSMS).<br>
2. Idnetified the KPIs for the given data.<br>
3. Utilized SQL queries within SSMS to perform initial data analysis and validation.<br>
4. Imported the analyzed data from SQL Server into Power BI for advanced visualization and dashboard creation.<br>
5. Employed Power Query Editor in Power BI to clean and transform the data.
    + Replaced the initial values of column pizza_size to their long form.
    + Added columns of month and day by extracting data from the order_date column.
6. Loaded and applied the cleaned data into Power BI for further processing.<br>
7. Designed an intuitive and user-friendly dashboard layout in Power BI.<br>
8. Created new measures to aggregate and display key data points using DAX functions.<br>
    - Added the KPI Average Pizza per Order.
    - Added the KPI Average Order Value.
    - Added the KPI Total Orders.
9. Incorporated various visualizations to enhance data representation, including:
    - Cards for key performance indicators (KPIs)
    - Stacked Column Chart for daily trend analysis.
    - Line Chart for monthly trend analysis.
    - Donut Chart for category breakdowns.
    - Funnel Chart for Pizzas sold by category.
    - Stacked Bar Charts for comparative analysis of top 5 and bottom 5 pizzas. 
10. Integrated slicer for filtering data by order date, enhancing interactivity.<br>
11. Included additional informative KPIs to provide quick insights into key metrics.<br>
12. Created interactive buttons to navigate to another page featuring visuals for the best and worst performing pizzas.<br>

# Features:
**Revenue and Sales Overview**<br>
Total revenue, average order value, total pizzas sold, total orders, and average pizzas per order are prominently displayed for a high-level understanding of sales performance.

**Sales Trend Analysis**<br>
Daily trend of total orders represented through a bar chart.
Monthly trend of total orders depicted using a line chart, enabling identification of peak and low seasons.

**Product Performance Analysis**<br>
Sales breakdown by pizza category and pizza size using a donut chart.
Total pizzas sold by category shown through a funnel chart.

**Busiest Time Insights**<br>
Busiest days of the week based on maximum orders received.
Busiest months based on maximum orders received.

**Best and Worst Sellers**<br>
Top 5 and Bottom 5 pizzas ranked by revenue, quantity, and total orders.<br>
Enables quick identification of best-selling and underperforming pizzas.

**Sales Performance Highlights**<br>
Enables quick identification of the best-selling pizza on the basis of size and category.<br>

Overall, the dashboard provides a comprehensive view of sales performance, product analysis, trend identification, and insights into peak demand periods for effective decision-making.

# Usage
Leverage the provided dataset and Power BI reports to gain deep insights into pizza sales in a pizzeria. Tailor the analysis by integrating additional data sources or refining predictive models. Utilize this repository as a valuable resource for mastering Power BI techniques in pizza sales.<br>
The Pizza Sales Analysis Dashboard can be utilized by pizzeria owners, managers, and stakeholders to monitor sales performance, identify trends, analyze product popularity, and make data-driven decisions to optimize operations and drive business growth.

# Acknowledgments
The Power BI dashboard template was inspired by various online resources and tutorials.<br>
Special thanks to the call center data analytics community for their valuable insights and best practices.
