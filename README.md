# Pizza Sales Analysis

## Project Overview

This project analyzes pizza sales data to understand revenue trends, time‑based patterns, and moving‑average behavior. The goal is to clean the data, build clear KPIs, explore key insights, and visualize the results through an interactive dashboard.

## Tools Used
   
Excel

Power Query

Data Cleaning & Transformation

Power Pivot & Data Modeling

DAX

PivotTables

Data Visualization

## Dataset Overview

The dataset includes four main tables:

orders

order_details

pizzas

pizza_types

Each table contains information related to orders, quantities, pizza sizes, categories, and pricing.

## Data Cleaning 

A brief overview of the main cleaning steps:

Fixed missing values in date and ID fields

Removed negative and extreme quantity values

Standardized size labels (small, medium, large)

Removed duplicates

Deleted unnecessary columns (e.g., ingredients in pizza_types)

Corrected data types for dates and time fields

Used Power Query to clean and structure the data, ensuring all steps are saved and automatically applied to any new data.

(Full cleaning details are documented inside the Excel file "Documentaion Sheet")

## Key Performance Indicators (KPIs)

Total Revenue

Total Orders

Total Quantity Sold

Average Quantity per Order

These KPIs summarize overall business performance.

## Key Insights
Classic pizzas generate the highest revenue and quantity.

Large pizzas are the most popular and profitable size, while XL and XXL have very low demand.

Peak order time is between 12–1 PM, driven by lunch demand.

Monthly revenue shows clear peaks in March, May, and July, but the month‑to‑month values were unstable and showed noticeable fluctuations. Using a 3‑month moving average helped smooth out these variations and reveal the underlying trend: steady growth from March to July, a decline until October, and stable levels toward the end of the year.

## Dashboard
The dashboard visualizes:

Category performance

Size performance

Time‑based trends

KPIs

Monthly revenue and moving average

![photo_2026-02-07_16-38-45](https://github.com/user-attachments/assets/7eadfb3c-9dcb-4e11-aa71-0b0ff746df0e)

## How to Use This Project
Download the Excel file.

For view the Power Query Steps The Excel file includes all data‑cleaning logic inside Power Query. 
To view the applied steps: 1. Open **pizza_sales.xlsx**. 2. Go to **Data** → **Get Data** → **Launch Power Query Editor**.

Open the Dashboard sheet to explore the visuals.

Use slicers to filter by category, size, or month.

To refresh the data: Data → Refresh All.

Power Query will update all tables and PivotTables automatically.

## Project Files
- [pizza_sales.xlsx](https://github.com/NatalyAnbar/Pizza-Sales-Analysis/blob/main/ProjectFiles/ProjectFile/pizza_project.xlsx) — cleaned data, pivot tables, dashboard, documentation   

### Raw Dataset (CSV files)
- [orders.csv](https://github.com/NatalyAnbar/Pizza-Sales-Analysis/blob/main/ProjectFiles/Raw%20DataSet/Orders.csv)  
- [order_details.csv](https://github.com/NatalyAnbar/Pizza-Sales-Analysis/blob/main/ProjectFiles/Raw%20DataSet/Orders_details.csv)  
- [pizzas.csv](https://github.com/NatalyAnbar/Pizza-Sales-Analysis/blob/main/ProjectFiles/Raw%20DataSet/Pizzas.csv)  
- [pizza_types.csv](https://github.com/NatalyAnbar/Pizza-Sales-Analysis/blob/main/ProjectFiles/Raw%20DataSet/pizza_types.csv)
