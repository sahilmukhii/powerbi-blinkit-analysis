# Blinkit Power BI Dashboard

This project is an interactive Power BI dashboard built to analyze Blinkit's retail performance using mock data. It provides a clear picture of key business metrics such as total sales, outlet performance, item-level trends, and customer ratings.

The dashboard is fully interactive, allowing users to filter data by outlet location, size, and item type. It’s designed to simulate a real-world business scenario and demonstrate how Power BI can turn raw data into actionable insights.

## What the Dashboard Shows

- Total Sales, Average Sales, Total Items Sold, and Average Customer Ratings
- Year-wise trend of outlet establishments (from 2010 to 2022)
- Breakdown of sales by item types like Fruits, Dairy, Meat, etc.
- Fat content comparison (Low Fat vs Regular)
- Performance by outlet tiers (Tier 1, 2, 3), size (Small, Medium, High), and type (Supermarket, Grocery Store)
- A detailed performance matrix showing sales, average rating, and item visibility

## Tools & Technologies Used

This project was built entirely in Power BI Desktop. Here's a quick overview of the tools used:

- **Power Query**: Used for data cleaning, transformation, and combining multiple tables
- **Data Modeling**: Structured using a star schema with fact and dimension tables
- **DAX (Data Analysis Expressions)**: Created calculated columns and measures to compute KPIs
- **Power BI Visuals**: Used a combination of bar charts, donut charts, line graphs, and matrix tables for clarity and interactivity

## ETL & Data Modeling Approach

The raw data was loaded and cleaned using Power Query. This included removing nulls, renaming columns, filtering unnecessary data, and adding calculated columns such as sales revenue and item visibility.

For modeling, a star schema was used where the sales transactions form the fact table, and lookup tables include product details, outlet information, date, fat content, and outlet size. This structure makes it easy to slice and filter data without performance issues.

## How to Use This Project

1. Download the `.pbit` file from this repository.
2. Open it using Power BI Desktop.
3. Connect your own dataset if needed.
4. Interact with the filters and visuals to explore insights.

## About the Data

This project is based on mock data and is meant for learning, portfolio building, and demonstrating Power BI capabilities. No real or confidential data from Blinkit is used.

---

If you have feedback or suggestions, you’re welcome to open an issue.

