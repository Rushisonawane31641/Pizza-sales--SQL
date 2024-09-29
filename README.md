# 🍕 Pizza Sales SQL Portfolio Project

This project analyzes pizza sales data using SQL. The datasets contain various metrics, such as pizza types, orders, customers, and more, which are used to answer predefined business questions. The project is executed in **MySQL Workbench**.

## 📁 Project Structure

- /datasets/: Contains the datasets used for analysis in excel format.
- /queries/: SQL queries used to perform the analysis.
- Pizza_sales_project.sql: Main SQL file containing all the necessary queries for solving the business questions.

 📊 Datasets

The project uses the following datasets:
1. pizzas.excel - Information about different types of pizzas.
2. orders.excel - Data regarding customer orders.
3. pizza_types.excel - Descriptions of pizza types and their ingredients.
4. order_details.excel - Detailed information about each order placed.


💻 How to Run the Project

 Prerequisites
- MySQL Workbench installed on your system.
- Import the datasets into your MySQL Workbench environment.

Steps
1. Clone the repository:
    ```bash
    git clone https://github.com/Rushisonawane31641/Pizza-sales--SQL.git
    ```
2.  Import datasets:
   - Open MySQL Workbench.
   - Create a new schema (database) named `pizza_sales`.
   - Use the MySQL Workbench's import feature to load the CSV files into tables.
     - `pizzas.csv` into `pizzas` table.
     - `orders.csv` into `orders` table.
     - `pizza_types.csv` into `pizza_types` table.
     - `order_details.csv` into `order_details` table.
    

3.   Run the SQL scripts:
   - Open `Pizza_sales_project.sql` file in MySQL Workbench.
   - Execute the queries to generate insights and answer the business questions.

📌 Key SQL Concepts

- Joins: Combining multiple tables to retrieve relevant data.
- Aggregations: Summing up totals, averages, and other metrics.
- Filtering: Using `WHERE` clauses to refine the results.
- Sorting: Ordering the data using `ORDER BY`.

 🚀 Technologies Used

- MySQL Workbench: Used for database management and executing SQL queries.
- SQL: Query language for extracting insights from the datasets.

 🧑‍💻 Author

- Harshal Sonawane - [GitHub](https://github.com/Rushisonawane31641)

 🤝 Contributions

Feel free to fork this project and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

