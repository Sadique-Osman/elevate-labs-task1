# Task 1 - Data Cleaning and Preprocessing

## Internship
Elevate Labs - Data Analyst Internship

## Objective
Clean and prepare a raw dataset with nulls, duplicates and inconsistent formats using Python Pandas.

## Dataset
- Name: Car Prices Dataset
- Rows: 558,837 | Columns: 16
- Source: https://www.kaggle.com/datasets/syedanwarafridi/vehicle-sales-data

## Tool Used
- Python, Pandas
- Google Colab

## Steps Performed
1. Loaded dataset and inspected shape, dtypes and missing values
2. Removed duplicate rows
3. Filled missing values with "Unknown"
4. Renamed all columns to lowercase
5. Standardized text columns to Title Case
6. Fixed data types for year, odometer, mmr, sellingprice
7. Cleaned saledate column to dd-mm-yyyy format
8. Saved final cleaned file

## Result
Final cleaned dataset: 99,812 rows × 16 columns
