# RUSH Sales Analysis

## Project Overview

This project analyzes raw sales data for RUSH, a global sportswear and footwear company. The goal is to identify trends and insights related to products, retailers, locations, and sales methods.

## Business Questions

The analysis addresses the following questions:

1. What product category had the highest sales in dollars in 2021?
2. What state had the highest sales of women's products in 2021?
3. What state had the highest sales of men's products in 2021?
4. What retailer purchased the most units in 2021 and 2020?

## Data

The analysis uses three tables:

* `TABLE_PRODUCTS`
* `TABLE_RETAILER`
* `TABLE_SALES`

The original data was raw and required data-quality checks and cleaning before analysis.

## Data Cleaning

The following data-quality issues were addressed:

* Invalid values in the `UNITS_SOLD` field
* Missing `PRICE_PER_UNIT` values
* An unrealistic price value
* A spelling error in the sales method field
* Data type conversion for numerical analysis

## Key Findings

* Men's Street Footwear was the highest-selling product category in 2021, generating approximately $23.28 million.
* Maine had the highest women's product sales in 2021, at approximately $2.18 million.
* Delaware had the highest men's product sales in 2021, at approximately $2.33 million.
* Foot Locker purchased the most units in 2021, with approximately 1.10 million units.
* Amazon purchased the most units in 2020, with approximately 316,880 units.
* Online sales represented an important sales channel for RUSH.

## Tools

* Python
* Google Colab
* GitHub
