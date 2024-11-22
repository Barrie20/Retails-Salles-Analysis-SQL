# Retail Sales Analysis SQL Project

## Overview
Welcome to my Retail Sales Analysis project! This repository contains a comprehensive SQL project designed to set up a retail sales database, perform data cleaning, and conduct exploratory data analysis (EDA). The ultimate goal is to derive actionable insights from the sales data.

## Objectives
1. **Database Setup**: 
   - Creation of a robust retail sales database named `p1_retail_db`.
   - Development of a `retail_sales` table to store essential sales data, including transaction ID, sale date, sale time, customer ID, gender, age, product category, quantity sold, price per unit, cost of goods sold (COGS), and total sale amount.

2. **Data Cleaning**: 
   - Identification and removal of records with missing or null values to ensure data integrity.

3. **Exploratory Data Analysis (EDA)**: 
   - Basic analysis to understand the dataset's characteristics, including record counts and unique entries.

4. **Business Analysis**: 
   - Utilization of SQL queries to answer specific business questions and extract valuable insights from the sales data.

## Project Structure
- **Database Setup**: The project initializes the database and creates the sales table with the following SQL commands:
  ```sql
  CREATE DATABASE p1_retail_db;
  CREATE TABLE retail_sales(
      transactions_id INT PRIMARY KEY,
      sale_date DATE,
      sale_time TIME,
      customer_id INT,
      gender VARCHAR(10),
      age INT,
      category VARCHAR(35),
      quantity INT,
      price_per_unit FLOAT,
      cogs FLOAT,
      total_sale FLOAT
  );
  ```

- **Data Exploration & Cleaning**: This section includes SQL queries to:
  - Count total records: `SELECT COUNT(*) FROM retail_sales;`
  - Count unique customers: `SELECT COUNT(DISTINCT customer_id) FROM retail_sales;`
  - Identify unique product categories: `SELECT DISTINCT category FROM retail_sales;`

## Insights
By analyzing this dataset, I aim to uncover patterns and trends that can drive business decisions and enhance sales strategies. The analysis will serve as a foundation for further exploration into customer behavior, product performance, and operational efficiencies.

## Tools and Technologies
- SQL (Structured Query Language)
- Database Management Systems (e.g., MySQL, PostgreSQL)
- Data Visualization Tools (for future extensions)

Feel free to explore the code and contribute to the project. Your feedback and suggestions are highly appreciated!
