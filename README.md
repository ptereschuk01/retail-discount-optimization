# Retail Discount Optimization Analysis

## Overview

This project analyzes how price discounts influence product sales and profitability in retail.

Retail companies frequently use discounts to increase sales. However, excessive discounts can significantly reduce profit margins. The goal of this project is to analyze the relationship between discount levels, sales volume, and profit in order to identify the optimal discount strategy.

The analysis is based on retail sales data and includes an interactive dashboard that allows exploration of product performance under different discount levels.

---

## Business Problem

Retail companies often apply discount campaigns to stimulate demand. While discounts can increase sales volume, they may also significantly reduce profit margins.

The key business question addressed in this project is:

**Which discount level maximizes profit while maintaining strong sales performance?**

Without data-driven analysis, companies may face:

- unnecessary margin losses
- inefficient promotions
- suboptimal pricing strategies

---

## Project Goal

The goal of this project is to analyze the relationship between:

- discount levels
- sales quantity
- profit

and identify the discount level that maximizes overall profitability.

---

## Dataset

The dataset contains retail sales transactions with the following fields:

| Column | Description |
|------|-------------|
| Date | Sales date |
| Store | Store location |
| Product | Product name |
| Category | Product category |
| SubCategory | Product subcategory |
| Qty | Quantity sold |
| Cost | Purchase cost |
| Price | Original price |
| Discount | Applied discount |
| Price_Discounted | Price after discount |
| Profit | Total profit |

---

## Analysis Steps

The project includes several stages of data analytics:

### Data Preparation

- validation of dataset structure
- checking for missing values
- calculation of discounted price
- calculation of profit

Profit formula:
