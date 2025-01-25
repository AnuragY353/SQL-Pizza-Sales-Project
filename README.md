# Pizza Sales Data Analysis using SQL
## Overview
This project focuses on analyzing pizza sales data using SQL. The analysis uncovers key business insights, such as sales trends, customer preferences, and revenue patterns, to help optimize business strategies in the food and beverage industry.

### Project Objectives
Retrieve the total number of orders placed and total revenue generated.
Identify the most popular pizza types, sizes, and highest-priced pizzas.
Analyze sales trends by date and time to understand customer behavior.
Perform category-wise and revenue-based analysis of pizza sales.
Provide actionable insights based on advanced analytics like cumulative revenue and contribution percentages.
Database Structure

### The database consists of four tables:

1. pizzas Table
Stores details about each pizza, including its size, type, and price.

Columns: pizza_id, pizza_type_id, size, price.
2. pizza_types Table
Contains information about pizza categories and their ingredients.

Columns: pizza_type_id, name, category, ingredients.
3. orders Table
Records details about each customer order.

Columns: order_id, order_date, order_time.
4. order_details Table
Links pizzas to specific orders, capturing quantities ordered.

Columns: order_details_id, order_id, pizza_id, quantity.
Analysis Performed

### Basic Analysis
Total orders and revenue calculation.
Identification of highest-priced pizzas.
Most popular pizza sizes and top 5 pizza types.

### Intermediate Analysis
Distribution of orders by time and category.
Average pizzas ordered per day.
Revenue-based ranking of pizza types.

### Advanced Analysis
Percentage contribution of each pizza type to total revenue.
Cumulative revenue trends over time.
Top pizza types by revenue and category.

### Technologies Used
SQL: For querying and analysis.
Database Management System: MySQL or any RDBMS.
Visualization: (Optional, mention tools like Excel, Tableau, or Python if used for graphs).

### How to Use
Clone the repository:
bash
Copy
Edit
git clone https://github.com/yourusername/pizza-sales-analysis.git
Import the provided SQL scripts and dataset into your SQL database.
Use the SQL queries from the project to perform analyses and generate insights.

## Project Highlights
Clear insights into sales trends and customer preferences.
Advanced revenue analysis to aid in decision-making.
Optimized SQL queries for efficient data retrieval.

### Future Enhancements
Integrate visualization tools like Tableau or Power BI for dynamic dashboards.
Expand the dataset to include delivery times and customer feedback for deeper insights.
Automate SQL query execution and report generation.

### Contributing
Feel free to submit issues or pull requests if you'd like to contribute to this project. All contributions are welcome!

### License
This project is licensed under the MIT License.

