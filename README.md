1. Project Overview

This project focuses on analyzing pizza sales data using Microsoft Excel.
The goal is to generate business insights such as best-selling pizzas, revenue trends, category-wise sales distribution, and peak order times.

The repository contains multiple raw data files and an Excel workbook with pivot tables, charts, and dashboards.

2. Dataset & Files

The repository includes:

orders.csv — Order-level details (order ID, date, time, etc.)

order_details.csv — Breakdown of items per order (pizza, quantity, price)

pizzas.csv — Pizza details (name, size, price)

pizza_types.csv — Metadata about pizza categories/types

PizzaSalesAnalysis.xlsx — Excel workbook containing the analysis & dashboard

3. Objectives & Key Questions

Key objectives of this project:

Calculate Total Revenue, Total Orders, Total Pizzas Sold

Find Average Order Value and Average Pizzas per Order

Identify sales contribution by Pizza Category and Size

Highlight Top 5 and Bottom 5 Pizzas by revenue, quantity, and order count

Understand time-based trends (hourly, daily, monthly)

Provide business recommendations from the data

4. Methodology / Workflow

Data Preparation

Import CSV files into Excel

Merge orders, order_details, pizzas, and pizza_types

Clean missing values, fix data types (dates/times), standardize pizza sizes

KPI Calculation

Revenue = sum(price × quantity)

Total Orders = count of unique order IDs

Total Pizzas Sold = sum of quantity

Average Order Value = Total Revenue ÷ Total Orders

Average Pizzas per Order = Total Pizzas ÷ Total Orders

Analysis

Category-wise and size-wise sales performance

Ranking of pizzas (best and worst performers)

Day-of-week and time-of-day sales trends

Dashboard & Visualization

Created with Pivot Tables and Charts in Excel

Includes bar charts, pie charts, and trend lines

5. Insights & Key Findings

(Sample insights – to be refined after reviewing the Excel dashboard)

Classic pizzas generate the highest revenue share.

Large pizzas are the most frequently ordered size.

Thai Chicken Pizza is among the top sellers, while Brie Carre Pizza has the lowest sales.

Peak order times: Lunch (12–1 PM) and Dinner (6–8 PM).

Fridays and Saturdays see the highest order volume.
