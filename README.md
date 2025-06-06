# 🛒 SQL Retail Sales Analysis

A complete end-to-end SQL project analyzing a retail sales dataset. This project demonstrates database setup, data cleaning, and the use of advanced SQL queries to derive actionable business insights.

---

## 🎯 Project Objectives

- ✅ Set up a structured **retail sales database**
- ✅ Perform **data cleaning** and remove incomplete records
- ✅ Conduct **exploratory data analysis (EDA)** using SQL
- ✅ Answer **key business questions** with real-world insights

---

## 🧱 Project Structure

1. **Database Setup**
   - Created a database: `p1_retail_db`
   - Created a table: `retail_sales` with key fields:
     `transaction_id`, `sale_date`, `customer_id`, `category`, `price`, `total_sale`, etc.

2. **Data Exploration & Cleaning**
   - Counted total records and unique customers
   - Identified unique product categories
   - Removed records with NULL values to ensure data quality

3. **Business Analysis (SQL Queries)**
   - Top-selling product categories
   - Sales by gender and category
   - High-value transactions (total_sale > 1000)
   - Best-selling month of each year
   - Shift-wise order analysis (Morning, Afternoon, Evening)
   - Top 5 customers by total spending

---

## 💡 Key SQL Techniques Used

- `GROUP BY`, `ORDER BY`, `JOIN`, `COUNT(DISTINCT ...)`
- `CASE WHEN` for time-based segmentation
- `EXTRACT()` and `TO_CHAR()` for date manipulation
- `RANK()` window function to identify peak sales periods

---

## 📌 Sample Business Insights

- **Clothing & Beauty** are high-performing product categories.
- **Evening shift** sees the most sales, suggesting customer activity after work hours.
- Top 5 customers generate a significant share of total sales — ideal for loyalty targeting.
- Peak sales months vary by year, indicating seasonal trends.

---

## 🛠️ Tools Used

- **SQL** (PostgreSQL / MySQL)
- **DBMS**: pgAdmin / MySQL Workbench / SQLite (flexible)
- **Dataset**: Simulated retail data (custom CSV)

---

## 📂 Files

```bash
📦 SQL_Retail_Sales_Project/
├── SQL Retail sales Project.pdf      # Project overview and queries
├── retail_sales.csv                  # Sample dataset (optional)
├── README.md                         # Project documentation
