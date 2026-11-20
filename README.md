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
---

# TDI Week 3: Data Structures & the Supply Chain Network

## Project Overview

Week 3 focused on applying Python's built-in data structures to analyse supplier relationships, purchasing activities, and potential supply chain risks.

Using the same supply chain dataset containing 3,000 purchase orders, I applied lists, dictionaries, sets, and nested dictionaries to organise information and generate business insights.

## Project Objectives

- Use lists to organise and analyse order costs.
- Apply dictionaries to map product categories to suppliers.
- Use sets to identify unique suppliers, categories, and delivery statuses.
- Apply set operations to compare supplier relationships.
- Identify single-source supply risks.
- Build a nested dictionary representing the supplier network.
- Analyse high-value orders and supplier category coverage.

## Tools and Technologies

- Python
- Jupyter Notebook
- Python `csv` module
- Lists, dictionaries, sets, and nested dictionaries
- Git and GitHub

## Tasks Completed

1. Extracted order costs into a list and calculated total spend, average order value, and median order value.
2. Created a dictionary mapping product categories to their suppliers.
3. Used sets to identify unique suppliers and categories and investigate inconsistent naming.
4. Applied set operations to compare suppliers serving Motors and Pumps.
5. Identified product categories dependent on a single supplier.
6. Created a nested supplier network containing category coverage, order counts, and total spending.
7. Identified high-value orders exceeding 100,000.
8. Compared supplier category coverage.

## Key Findings

### Order Cost Analysis

- Total orders: 3,000.
- Total recorded order cost: 170,038,100.28.
- Average order value: 56,679.37.
- Median order value: 30,911.19.
- Highest recorded order cost: 1,720,595.40.
- Lowest recorded order cost: -207.32.

### Supplier and Category Analysis

- Standardised suppliers identified: 5.
- Product categories identified: 8.
- Original supplier-name variations: 15.
- SupplierB and SupplierC had the highest category coverage, with 3 categories each.

### Supplier Network Analysis

| Supplier | Orders | Categories | Total Spend |
|---|---:|---:|---:|
| SupplierA | 769 | 2 | 70,637,594.46 |
| SupplierB | 659 | 3 | 43,099,108.00 |
| SupplierC | 492 | 3 | 23,085,480.95 |
| SupplierD | 433 | 2 | 28,449,003.78 |
| SupplierE | 647 | 2 | 4,766,913.09 |

SupplierA recorded the highest order volume and total spend.

### Single-Source Supply Risk

Four out of eight product categories (50%) had only one recorded supplier:

- Fasteners — SupplierE.
- Control Systems — SupplierA.
- Connectors — SupplierE.
- Hydraulics — SupplierD.

SupplierE was the sole recorded supplier for two categories, indicating potential supplier concentration risk.

### High-Value Order Analysis

- Orders exceeding 100,000: 478.
- Percentage of all orders: 15.93%.

## Business Insights

The analysis revealed that some product categories depend on a single supplier, creating potential supply concentration risks.

SupplierB and SupplierC provide the widest category coverage, while SupplierA accounts for the highest recorded order volume and spending.

These findings demonstrate how Python data structures can help organise supply chain information and support procurement analysis.

## Skills Demonstrated

- Python lists and list comprehensions.
- Dictionary creation and manipulation.
- Set operations and data standardisation.
- Nested dictionaries.
- Loops and conditional statements.
- CSV file processing.
- Numerical analysis.
- Supplier network analysis.
- Supply chain risk identification.
- Business interpretation of analytical findings.

## Project Learning Outcome

This project strengthened my understanding of Python data structures and their practical applications in data analytics.

I learned how to organise complex relationships between suppliers and product categories, identify potential sourcing risks, and extract meaningful business insights from structured data.

It also improved my ability to translate programming results into findings that can support business decision-making.

## Project Notebook

[TDI Week 3 - Data Structures & Supply Chain Network](TDI_Week_3_Data_Structures_Supply_Chain_Network.ipynb)

---

**Learning Programme:** The Data Immersed School (TDI)  
**Project:** Week 3 - Data Structures & the Supply Chain Network

