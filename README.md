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
Imported raw sales data into SQL Server using the Import Task option in SQL Server Management Studio (SSMS).<br>
Idnetified the KPIs for the given data.<br>
Utilized SQL queries within SSMS to perform initial data analysis and validation.<br>
Imported the analyzed data from SQL Server into Power BI for advanced visualization and dashboard creation.<br>
Employed Power Query Editor in Power BI to clean and transform the data.<br>
Loaded and applied the cleaned data into Power BI for further processing.<br>
Designed an intuitive and user-friendly dashboard layout in Power BI.<br>
Created new measures to aggregate and display key data points using DAX functions.<br>
Incorporated various visualizations to enhance data representation, including:
- Card charts for key performance indicators (KPIs)
- Area charts for trend analysis
- Donut charts for category breakdowns
- Bar charts for comparative analysis

Integrated slicer for filtering data by order date, enhancing interactivity.<br>
Included additional informative KPIs to provide quick insights into key metrics.<br>
Created interactive buttons to navigate to another page featuring visuals for the best and worst performing pizzas.<br>

