# 🍕 Pizza Sales SQL Project

## 📌 Overview
This project analyzes a pizza sales dataset using **PostgreSQL**. It includes 13 well-structured queries — from basic aggregations to advanced window functions — to extract deep business insights related to sales, customer behavior, and product performance.

> 📍 Tools: PostgreSQL (pgAdmin)  
> 📍 Skills: SQL Joins, Aggregations, CTEs, Window Functions, Optimization

---

## 📊 Dataset Structure

| Table Name      | Description |
|----------------|-------------|
| `orders`        | Contains `order_id`, `date`, and `time` of orders |
| `order_details` | Contains `order_details_id` ,`order_id` ,`pizza_id` and `Quantity` |
| `pizzas`        | Contains `pizza_id`, `size`, `price`, `pizza_type_id` |
| `pizza_types`   | Contains `pizza_type_id`, `category`, `name`, `ingredients` |

---

## ✅ Project Objectives
Basic
Retrieve the total number of orders placed

Calculate the total revenue generated from pizza sales

Identify the highest-priced pizza

Identify the most common pizza size ordered

List the top 5 most ordered pizza types along with their quantities

Intermediate
Join the necessary tables to find the total quantity of each pizza category ordered

Determine the distribution of orders by hour of the day

Join relevant tables to find the category-wise distribution of pizzas

Group the orders by date and calculate the average number of pizzas ordered per day

Determine the top 3 most ordered pizza types based on revenue

Advanced
Calculate the percentage contribution of each pizza type to total revenue

Analyze the cumulative revenue generated over time

Determine the top 3 most ordered pizza types based on revenue for each pizza category



---

## 💡Insight & Recommendation
**Revenue & Volume**

Total revenue: $817,860 from 21,350 orders

Avg. 138 pizzas sold daily

**Product Performance**

🏆 Top pizza: Thai Chicken ($43.4K revenue)

🥇 Most ordered: Classic Deluxe (2,416 orders)

💰 Highest-priced: Greek Pizza ($35.95)

**Customer Behavior**

⏰ Peak hours: 12 PM (2,520 orders), 6 PM (2,399 orders)

📦 Size preference: Large (L) pizzas = 87% of orders

**Category Trends**

Classic pizzas drive 27% of revenue (highest share)

Veggie/Supreme categories have most varieties (9 types each) but lower sales


---

## 🧠 Interview Value

This project helps you explain:

- Your SQL skills with optimized, readable queries
- How you derive business insights from raw data
- End-to-end data storytelling from query to decision-making
---

## 📁 Folder Structure
1. orders.csv  
2. order_details.csv  
3. pizza_type.csv  
4. pizzas.csv  
5. PDF containing queries with their output and insights.

