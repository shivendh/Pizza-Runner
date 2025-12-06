# 🍕 Pizza Runner – SQL Data Analysis Project

## 📌 Project Overview
Pizza Runner is a SQL-based data analysis project focused on evaluating a fictional pizza delivery business. The project analyzes customer orders, runner deliveries, pizza ingredients, pricing, and operational performance to generate meaningful business insights using SQL queries.

This repository demonstrates **data cleaning, relational joins, aggregations, and analytical problem-solving using SQL**.

---

## 🧠 Business Problem
Pizza Runner wants to understand:
- Order and delivery performance
- Customer ordering behavior
- Runner efficiency and delivery success
- Ingredient usage and customization patterns
- Revenue, costs, and profitability

The SQL queries answer real-world analytics questions across multiple business dimensions.

---

## 📂 Dataset & Tables
The database consists of the following tables:

- **runners** – Runner registration details  
- **customer_orders** – Pizza orders placed by customers  
- **runner_orders** – Delivery, distance, duration, and cancellation data  
- **pizza_names** – Pizza types (Meatlovers, Vegetarian, etc.)  
- **pizza_recipes** – Ingredients used per pizza  
- **pizza_toppings** – Topping reference table  
- **runner_ratings** – Customer ratings for successful deliveries  

---

## 🧹 Data Cleaning Highlights
- Converted `'null'` string values into actual `NULL`
- Normalized inconsistent distance and duration formats
- Cleaned cancellations and delivery status fields
- Ensured accurate delivery-based analysis

---

## 📊 Analysis Sections

### 🔹 Part A: Pizza Metrics
- Total pizzas ordered
- Unique customer orders
- Successful deliveries per runner
- Pizza type distribution
- Customer-wise ordering behavior
- Peak order hours and weekdays
- Customizations (extras & exclusions)

---

### 🔹 Part B: Runner & Delivery Analysis
- Runner sign-up trends
- Average pickup preparation time
- Relationship between order size and prep time
- Delivery distance per customer
- Delivery duration variability
- Runner speed analysis
- Delivery success percentage per runner

---

### 🔹 Part C: Ingredient Optimization
- Standard ingredients for each pizza
- Most common extras and exclusions
- Ingredient usage frequency
- Optimization insights for inventory planning

---

### 🔹 Part D: Pricing & Revenue
- Total revenue by pizza type
- Revenue with extra topping charges
- Runner payment model
- Net profit calculations after delivery payouts

---

### 🔹 Bonus Analysis
- Menu expansion (adding new pizza types)
- Database scalability considerations
- Schema design for new pizzas and recipes

---

## 🛠 SQL Concepts Used
- `JOIN` (INNER, USING)
- `GROUP BY`, `ORDER BY`
- Aggregation functions (`SUM`, `COUNT`, `AVG`)
- Conditional logic (`CASE WHEN`)
- String cleaning and casting
- Date & time functions
- Schema design & inserts

---

## 🚀 How to Run the Project
1. Create a database:
   CREATE DATABASE pizza_runner;
   USE pizza_runner;
Execute the Pizza_Runner.sql file:
- This will create tables, insert data, clean fields, and run analysis queries.
- Run queries section-wise to explore insights.

## 📈 Key Insights Generated
- Delivery success differs significantly across runners
- Customizations impact preparation time
- Certain toppings are used far more frequently
- Profitability depends heavily on delivery distance
- Peak demand follows specific time patterns

## 🎯 Use Cases
- SQL interview practice
- Data analyst portfolio project
- Business analytics case study
- Food delivery operations analysis

## ✅ Conclusion
The Pizza Runner project showcases how SQL can be used to solve complex, real-world business questions by combining data cleaning, relational modeling, and analytical querying. It highlights strong foundational skills in SQL and data analysis.
