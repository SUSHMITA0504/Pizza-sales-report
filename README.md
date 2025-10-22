# PIZZA SALES SQL ANALYSIS
About the Project

This is my first SQL analysis project that I created and uploaded on GitHub.
The project is based on a Pizza Sales dataset where I used PostgreSQL to analyze sales data and find useful insights like total revenue, top-selling pizzas, and sales by category.

# About the Dataset

The dataset is stored in a table named pizza_data.
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
order_date	Date of the order
order_time	Time of the order
Objectives of the Project

The main goal of this project was to write SQL queries that answer the following business questions:

What is the total revenue generated?

How many orders were placed?

How many pizzas were sold in total?

What is the average order value?

What is the average number of pizzas per order?

Which pizza categories performed the best?

Which are the top and bottom 5 pizzas by revenue, quantity, and orders?

Key Results
KPI	Value
Total Revenue	1795.75
Total Orders	20
Total Pizzas Sold	95
Average Order Value	89.79
Average Pizzas per Order	4.75
Some Observations

Veggie pizzas contributed the highest percentage of total sales.

The Thai Chicken Pizza generated the most revenue.

The Italian Supreme Pizza was the most frequently ordered pizza.

The Napolitana Pizza had the lowest sales.

SQL Concepts Used

Aggregate functions: SUM(), COUNT(), AVG()

Date functions: TO_CHAR(), EXTRACT()

Grouping and ordering with GROUP BY and ORDER BY

Subqueries and percentage calculations

Limiting results using LIMIT

Tools Used

PostgreSQL

DBeaver / pgAdmin for writing and running queries

GitHub for sharing and version control

What I Learned

How to calculate KPIs using SQL

How to analyze data using aggregate and date functions

How to find top and bottom performing items

How to use SQL for simple business insights

Author

Sushmita Kumari
Aspiring Business Analyst | Learning SQL, Excel, and Power BI
