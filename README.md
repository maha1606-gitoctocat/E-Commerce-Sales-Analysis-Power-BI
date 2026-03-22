# E-Commerce-Sales-Analysis-Power-BI


# 📊 Sales Dashboard Analysis using Power BI

## 📌 Project Overview

This project focuses on analyzing sales performance using **Power BI**, leveraging **DAX calculations** and interactive visualizations. The dashboard provides insights into revenue trends, profitability, customer behavior, and category performance to support data-driven decision-making.

## 🎯 Objectives

* Analyze **total sales, profit, and order performance**
* Track **Year-to-Date (YTD) growth**
* Compare **category and sub-category performance**
* Identify **high-performing regions (e.g., Delhi)**
* Evaluate **sales vs target achievement**
* Understand **customer purchasing behavior**


## 🗂️ Dataset Description

The dataset contains the following key fields:

* Order ID, Order Date
* Customer ID
* Product ID & Category/Sub-Category
* Quantity & Unit Price
* Discount & Payment Type
* Total Amount & Profit
* Store Information

## ⚙️ Data Modeling & DAX

### 📌 Calculated Columns

* **Category Type** = Category + Sub-Category
* **Revenue per Order** = Amount × Quantity
* **Sales Category** = Above/Below Average Revenue

### 📌 Measures

* **Order Count** = Total number of orders
* **Average Profit (Delhi)** = Profit filtered for Delhi region
* **YTD Sales** = Running total of revenue using time intelligence


## 📊 Dashboard Features

### 🔹 Sales Performance

* Total Revenue: **~₹4.8M**
* Total Orders: **~5,000**
* Average Revenue per Order: **~₹960**

### 🔹 Category Analysis

* Technology: **42% of total revenue**
* Furniture: **33%**
* Office Supplies: **25%**

### 🔹 Profit Insights

* Average Profit: **₹120 per order**
* Delhi Profit: **₹150 (higher than average)**

### 🔹 Time-Based Analysis

* Monthly Sales Trend (Line Chart)
* Year-to-Date (YTD) Growth Tracking

### 🔹 Target vs Actual

* Sales Target Achievement by Category
* Technology exceeded target (**105%**)

### 🔹 Product-Level Insights

* High Margin: Phones, Chairs
* Low Margin: Tables

### 🔹 Customer & Payment Insights

* Online Payments: **65%**
* Reward Customers generate **30% more revenue**

## 📈 Key Insights

* 📌 Technology category is the primary revenue driver
* 📌 Delhi is the most profitable region
* 📌 Sales show strong seasonal trends (peak in Nov–Dec)
* 📌 Majority of orders are below average value → upselling opportunity
* 📌 High sales volume does not always mean high profit


## 🛠️ Tools & Technologies

* **Power BI** – Data visualization
* **DAX (Data Analysis Expressions)** – Calculations & measures
* **Excel / CSV** – Data source



✅ Add **badges, portfolio links, and LinkedIn section**
✅ Make it **more advanced (recruiter-level GitHub)**
