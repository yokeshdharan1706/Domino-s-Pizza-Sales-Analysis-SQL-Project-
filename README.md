# 🍕 Domino’s Pizza Sales Analysis | SQL Project

## 📌 Project Overview

This project analyzes Domino’s Pizza sales data using **MySQL** to extract meaningful business insights.  
The objective is to understand customer ordering behavior, revenue trends, and product performance using structured SQL queries.

The project progresses from **Basic → Intermediate → Advanced SQL concepts**, demonstrating real-world business analytics use cases.

---

## 🗂️ Database Schema

The database consists of four relational tables:

### 🧾 Orders
- `order_id` (Primary Key)
- `order_date`
- `order_time`

### 📦 Order_Details
- `order_details_id` (Primary Key)
- `order_id` (Foreign Key)
- `pizza_id` (Foreign Key)
- `quantity`

### 🍕 Pizzas
- `pizza_id` (Primary Key)
- `pizza_type_id` (Foreign Key)
- `size`
- `price`

### 🏷️ Pizza_Types
- `pizza_type_id` (Primary Key)
- `name`
- `category`
- `ingredients`

---

## 📊 Business Questions Solved

### 🔹 Basic Analysis
- Total number of orders
- Total revenue generated
- Highest priced pizza
- Most commonly ordered pizza size
- Top 5 most ordered pizza types

### 🔹 Intermediate Analysis
- Total quantity ordered per pizza category
- Distribution of orders by hour
- Category-wise pizza distribution
- Average pizzas ordered per day
- Top 3 pizzas based on revenue

### 🔹 Advanced Analysis
- Percentage revenue contribution by category
- Cumulative revenue generated over time
- Top 3 pizzas by revenue within each category (Window Functions)

---

## 🛠️ SQL Concepts Used

- INNER JOIN
- GROUP BY
- ORDER BY
- LIMIT
- Subqueries
- CREATE VIEW
- SUM(), COUNT(), AVG()
- Date & Time Functions
- Window Functions
- RANK() OVER (PARTITION BY)

---

## 📈 Key Insights Generated

- Identified peak order hours
- Determined revenue-driving pizza categories
- Found best-selling pizzas
- Calculated daily average sales
- Analyzed cumulative revenue growth

---

## 🚀 How to Run

1. Create a MySQL database.
2. Import the pizza dataset tables.
3. Run the SQL queries provided in the project.
4. Execute the `CREATE VIEW` statements.
5. Use:

```sql
SELECT * FROM view_name;
