# 📁 Raw Data

## Dataset Information
- **Dataset:** Online Retail II
- **Source:** UCI Machine Learning Repository
- **File:** `data/raw/online_retail_ii.xlsx`

## Overview
This dataset contains real transactional data from a UK-based retail company.  
It includes information about orders, products, customers, prices, quantities, and countries.  
The data reflects real retail scenarios such as bulk purchases, repeat customers, and product returns.

## Key Columns
- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

## Important Notes
- Negative values in `Quantity` represent returned items  
- Some records contain missing `CustomerID` values  
- Sales channel (online vs offline) is not explicitly available and will be derived during analysis

## Usage
This raw dataset is kept unchanged to preserve data integrity.  
All data cleaning and transformations are performed on processed datasets.
