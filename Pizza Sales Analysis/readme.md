# Pizza Sales Dashboards

## Overview
This repository contains SQL queries and insights for analyzing pizza sales data. The provided queries calculate key performance indicators (KPIs), identify sales trends, and rank pizza performance by revenue, quantity, and orders. These scripts can be used to build interactive dashboards or reports for business decision-making.

---

## Key Features

### KPIs
- **Total Revenue**: Aggregates revenue across all orders.
- **Average Order Value**: Calculates the average revenue per order.
- **Total Pizza Sold**: Counts the total quantity of pizzas sold.
- **Total Orders**: Counts the distinct orders placed.
- **Average Pizzas per Order**: Provides the average number of pizzas per order.

### Trend Analysis
- **Daily Trend for Total Orders**: Tracks orders by the day of the week.
- **Monthly Trend for Total Orders**: Tracks orders by month.

### Category Analysis
- **Percentage of Sales by Pizza Category**: Computes sales percentage by pizza category overall and for specific months.
- **Percentage of Sales by Pizza Size**: Computes sales percentage by pizza size for specific months.

### Pizza Rankings
- **Top 5 Pizzas by Revenue**: Identifies the highest revenue-generating pizzas.
- **Bottom 5 Pizzas by Revenue**: Lists pizzas with the lowest revenue.
- **Top 5 Pizzas by Quantity Sold**: Ranks pizzas by total quantity sold.
- **Top 5 Pizzas by Orders**: Ranks pizzas by the number of distinct orders.

---

## SQL Queries
Each query is designed for use with a `pizza_sales` dataset, leveraging SQL for:
- Summarizing metrics
- Grouping data by time and categories
- Calculating percentages
- Sorting and limiting results for rankings

The SQL scripts are structured for clarity and reusability.

---

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pizza-sales-dashboards.git
   cd pizza-sales-dashboards
   ```
2. Ensure your database contains a table named `pizza_sales` with relevant fields (`total_price`, `order_id`, `pizza_name`, `pizza_category`, `pizza_size`, `quantity`, and `order_date`).
3. Execute the SQL scripts using your preferred database client.

---
