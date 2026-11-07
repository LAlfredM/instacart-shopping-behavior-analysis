# Instacart Shopping Behavior Analysis

## Project Overview

This project explores historical Instacart grocery orders to identify customer purchasing patterns, product preferences, and reorder behavior.

The analysis focuses on order frequency, purchasing schedules, popular products, cart composition, and customer reorder habits.

## Objectives

- Analyze order distribution by hour and day of the week.
- Identify purchasing patterns and reorder intervals.
- Determine the most frequently purchased and reordered products.
- Explore the number of items per order.
- Examine customer-level and product-level reorder proportions.

## Dataset

The project uses five CSV files containing historical Instacart order information:

- `instacart_orders.csv`
- `products.csv`
- `aisles.csv`
- `departments.csv`
- `order_products.csv`

The datasets include information about customer orders, product details, aisle and department classifications, and the products included in each order.

All five files are organized in the `Datasets/` directory within this repository.

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Project Workflow

1. **Data Loading:** Imported the five datasets and inspected their structure.
2. **Data Preprocessing:** Identified and handled missing values, duplicates, and data types.
3. **Exploratory Data Analysis:** Examined purchasing frequency, order schedules, product popularity, and reorder behavior.
4. **Data Visualization:** Created charts to identify distributions and purchasing patterns.
5. **Conclusions:** Summarized the main findings and potential business insights.

## Key Findings

- Most orders are concentrated during daytime hours.
- Weekly purchasing activity varies depending on the day.
- Order sizes show a right-skewed distribution, with larger orders increasing the average.
- Frequently purchased products include everyday grocery essentials.
- Reorder patterns reveal differences in customer purchasing behavior.

## Repository Contents

- `instacart_analysis.ipynb`: Complete data analysis and visualizations.
- `README.md`: Project documentation.
- `.gitignore`: Files and directories excluded from version control.