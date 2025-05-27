# Walmart_Data_Analysis

# 🛒 Walmart Sales Data Analysis using SQL

This project analyzes Walmart's sales data using SQL to uncover key business insights such as revenue trends, customer behavior, product performance, and operational metrics.

## 📁 Project Structure

- `WalmartSalesData.csv`: The raw transactional data containing details of over 1,000+ sales records including branch, product type, customer type, and more.
- `SQL_queries.sql`: A collection of SQL queries executed on the dataset to extract insights.

---

## 🧾 Dataset Overview

The dataset includes the following columns:

- `Invoice ID`, `Branch`, `City`, `Customer type`, `Gender`
- `Product line`, `Unit price`, `Quantity`, `Tax 5%`, `Total`
- `Date`, `Time`, `Payment`, `cogs`, `gross margin percentage`, `gross income`, `Rating`

---

## 📊 Key Analyses Performed

1. **Basic Insights**
   - Total number of sales
   - Number of unique product lines
   - Total gross income

2. **Sales Trends**
   - Monthly and daily revenue patterns
   - Peak sales hours using `EXTRACT(HOUR FROM Time)`
   - Sales by city and branch

3. **Customer Analysis**
   - Count and percentage of returning vs. new customers
   - Gender-based analysis and purchase behavior
   - Average rating by gender and product

4. **Product Performance**
   - Best and worst performing product lines
   - Total quantity sold per category
   - Revenue by product line

5. **Payment & Revenue**
   - Distribution of payment methods
   - Top 5 invoices by total amount
   - Gross income trends across branches
