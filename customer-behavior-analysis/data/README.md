# Data Directory

This directory contains all datasets used in the Customer Behavior Analysis project.
Data is organized by processing stage to maintain clarity, reproducibility, and best practices.

## Folder Structure

data/
├── raw/
│   └── customer_shopping_behavior.csv
├── processed/
│   └── (cleaned and transformed datasets will be stored here)

## Raw Data

**File:** `customer_shopping_behavior.csv`  
**Description:**  
Original customer shopping behavior dataset containing transaction-level information such as
customer demographics, product categories, and purchase amounts.

**Important:**
- Data in the `raw/` folder is **never modified**
- All cleaning, transformation, and feature engineering is performed on copies saved in `processed/`

## Processed Data

The `processed/` folder will contain:
- Cleaned datasets
- Feature-engineered datasets
- Analysis-ready tables used in notebooks and visualizations

Each processed file will be traceable to the notebook that created it.

## Data Usage

This data is used for:
- Exploratory Data Analysis (EDA)
- Customer segmentation analysis
- Spending pattern analysis
- Business insight generation

## Notes

- Any assumptions, data issues, or limitations discovered during analysis will be documented in the project notebooks.
