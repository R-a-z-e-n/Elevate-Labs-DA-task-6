# Task 6: Sales Trend Analysis Using Aggregations

## 📌 Objective
Analyze **monthly revenue** and **order volume** from sales data using SQL aggregations.

## 🛠 Tools
- MySQL (command line)
- SQL script

## 📂 Deliverables
- SQL script (`sales_trend.sql`)
- Results table (monthly revenue + order volume)

## 🧾 Schema
```sql
CREATE TABLE orders (
    order_id INT PRIMARY KEY,
    order_date DATE,
    customer_id INT,
    revenue DECIMAL(10,2)
);

