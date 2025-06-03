# Exploring and Cleaning Data with Pandas

This project focuses on analyzing the Instacart order dataset to explore customer behavior and ordering patterns using Python and pandas.

## 📁 Project Structure

- `Exploring_and_Cleaning_Data_with_Pandas.ipynb` — main notebook with all analysis steps
- datasets ([you can find them on my Google Drive](https://drive.google.com/drive/folders/10blCPoIDKsl7-MNaaA0CJ5UIfujM8YlN?usp=sharing))
    - `instacart_orders.csv` — each row corresponds to one order on the Instacart app
    - `products.csv` — each row corresponds to a unique product that customers can buy
    - `order_products.csv` — each row corresponds to one item placed in an order
    - `aisles.csv` — information about product aisles
    - `departments.csv` — information about product departments

## 🔍 Project Overview

**1. Data Preparation:**
- Conducted initial data review and validation of expected value ranges
- Removed duplicates and handled missing values
- Merged tables to form a comprehensive dataset for analysis

**2. Data Exploration and Analysis:**
- Verified the validity of `order_hour_of_day` and `order_dow` columns
- Visualized:
  - Order frequency by hour of the day
  - Order frequency by day of the week
  - Time delays between customer orders
- Compared order time distributions for selected days (e.g., Wednesday vs. Saturday)
- Analyzed the number of orders per customer

**3. Product-Level Analysis:**
- Identified the top 20 most frequently ordered products
- Calculated the typical number of items per order
- Identified the top 20 most frequently reordered products
- Computed reorder ratios per product and per customer
- Identified the top 20 products most often added to the cart first

## 📌 Key Tools and Libraries

- Python
- pandas
- matplotlib & seaborn for data visualization

## ✅ Outcome

The project demonstrates the full cycle of exploratory data analysis using pandas — from data cleaning and merging to detailed visualizations and insights about customer behavior.
