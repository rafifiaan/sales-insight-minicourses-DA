# 📊 Sales Insight - Mini Course (Data Analysis)

This project is part of a data analytics mini-course. It focuses on Exploratory Data Analysis (EDA) of a company's product sales dataset, including data cleaning, visualization, and deriving insights related to order volume, product categories, customer segments, and sales performance.

In addition to standard charts and summary insights, this notebook also includes a simple interactive dashboard built using Jupyter Notebook widgets. The dashboard allows users to dynamically filter sales data by deal size and instantly view changes across multiple visualizations (bar chart, line chart, and pie chart) — all within the notebook environment.

## ❓ Problem Statements

- Which product lines have the highest and lowest sales? Create a chart that is representable.
- Show sales performance over time, is there any pattern?
- How does deal size (small, medium, large) correlate with total sales? What is the percentage of contribution for each type of deal?

## 📁 Dataset Overview

The dataset contains historical sales records with the following columns:

- `ORDERNUMBER` (int): Unique ID of the order
- `QUANTITYORDERED` (int): Number of items ordered
- `PRICEEACH` (float): Price per unit
- `ORDERDATE` (datetime): Date of the order
- `STATUS` (string): Order status
- `PRODUCTLINE` (string): Product category
- `PRODUCTCODE` (string): Product identifier
- `CUSTOMERNAME` (string): Customer's name
- `CITY` (string): Customer's city
- `DEALSIZE` (string): Transaction size (Small, Medium, Large)

---

## 🔧 Steps Performed

### 1. Data Cleaning 🧹

- Checked for nulls → _No missing values found_
- Handled duplicate rows → _1 duplicate row removed_
- Fixed inconsistent date formatting
- Ensured correct data types for analysis

### 2. Exploratory Data Analysis 📈

- Analyzed sales distribution across months, product lines, and cities
- Visualized order trends and transaction types
- Created box plots and pie charts to explore deal size vs total sales

### 3. Key Insights 💡

- Medium-sized deals contributed the most to total sales (**~59.8%**)
- Most popular product line: **Classic Cars**
- Peak order months were **October and November**
- Top-performing cities and customer names identified

---

## 📌 Tools Used

- Python
- Pandas
- Matplotlib & Seaborn
- Jupyter Notebook

---

> Rafi Aliefian Putra Ramadhani  
> Mini Course Project RevoU – July 2025
