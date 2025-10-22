🍕 Pizza Sales SQL Analysis Project

📘 Project Overview

This project analyzes pizza sales data using PostgreSQL to uncover key business insights and performance metrics.
The analysis covers sales trends, category-wise contributions, and top-performing pizzas by revenue, quantity, and order count.

📁 About the Dataset

The dataset is stored in a table called pizza_data.
It contains information about pizza orders such as:

Column Name	Description

pizza_id	Unique ID for each pizza
order_id	Unique order number
pizza_name	Name of the pizza
pizza_category	Type of pizza (Classic, Veggie, Chicken, Supreme)
pizza_size	Size of pizza (S, M, L, XL)
quantity	Number of pizzas ordered
unit_price	Price of one pizza
total_price	Total price for that order
order_date	Date of order
order_time	Time of order

🎯 What I Tried to Find

In this project, I wrote SQL queries to find:

Total revenue made from pizza sales

Total number of orders

Total pizzas sold

Average order value

Average number of pizzas per order

Most popular pizza categories

Top and bottom 5 pizzas by revenue, quantity, and orders

📊 Few Key Results
KPI	Value
Total Revenue	1795.75
Total Orders	20
Total Pizzas Sold	95
Avg Order Value	89.79
Avg Pizzas per Order	4.75

Veggie pizzas brought in the highest sales percentage.

“The Thai Chicken Pizza” had the highest revenue.

“The Italian Supreme Pizza” was the most ordered.

“The Napolitana Pizza” had the lowest sales.

🧠 What I Learned

How to calculate KPIs using SQL (SUM, COUNT, AVG, etc.)

How to group data and calculate percentages

How to use TO_CHAR() and EXTRACT() for date analysis

How to find top and bottom performers using ORDER BY and LIMIT

💬 Notes

This project helped me practice SQL concepts and understand how data analysis works on real-like datasets.
I plan to do more such small SQL projects and improve my skills!











