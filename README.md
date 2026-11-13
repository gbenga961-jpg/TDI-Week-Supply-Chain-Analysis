# TDI Week 2: Supply Chain Data Exploration with Python

## Project Overview

This project is part of my Data Analytics learning journey with The Data Immersed School (TDI).

The project focuses on applying fundamental Python programming concepts to explore a supply chain dataset containing purchase order and delivery information.

The goal was to practise decision-making with conditional statements, automate repetitive tasks using loops, create reusable functions, and perform basic dataset exploration using Python's built-in CSV module.

## Project Objectives

- Apply `if`, `elif`, and `else` statements to business approval decisions.
- Use comparison and logical operators.
- Process multiple purchase orders using `for` loops.
- Create reusable Python functions.
- Read CSV files using `csv.DictReader`.
- Explore supplier names, order costs, and delivery statuses.
- Identify potential data-quality issues without modifying the original dataset.

## Tools and Technologies

- Python
- Jupyter Notebook
- Python `csv` module

## Dataset Description

The supply chain dataset contains **3,000 records and 16 columns** covering purchase orders, product categories, suppliers, order costs, delivery information, and product defects.

## Tasks Completed

1. Developed an order approval function based on purchase order value.
2. Used a `for` loop to process multiple orders.
3. Created a supplier reliability classification function.
4. Imported and explored the supply chain CSV dataset.
5. Investigated supplier-name variations, order costs, and delivery statuses.

## Key Findings

- Total records: 3,000.
- Total columns: 16.
- Supplier-name variations identified: 15.
- Highest order cost: 1,720,595.40.
- Lowest order cost: -207.32.
- Delivered orders: 2,340.
- Delivery percentage: 78%.

## Data Quality Observations

The initial exploration revealed:

- Inconsistent supplier naming caused by differences in spacing and capitalization.
- A negative order cost that requires further investigation.
- Missing information in some dataset fields.
- Inconsistent date formats.

These observations were documented for further investigation. No data cleaning or modification was performed because the focus of this week's project was data exploration.

## Business Questions

1. Which suppliers have the highest and lowest on-time delivery rates?
2. What factors contribute to the 22% of orders that do not have a Delivered status?
3. Why does the dataset contain a negative purchase order cost?

## Skills Demonstrated

- Python fundamentals
- Conditional statements
- Comparison and logical operators
- Loops
- Functions
- CSV file handling
- Basic data exploration
- Identifying data-quality issues
- Business thinking and analytical documentation

## Project Learning Outcome

This project strengthened my understanding of Python fundamentals and demonstrated how basic programming concepts can be applied to real-world business data.

It also helped me recognise the importance of examining data quality before proceeding to data cleaning and deeper analysis.

---

**Learning Programme:** The Data Immersed School (TDI)  
**Project:** Week 2 – Control Flow, Functions & First Dataset Exploration