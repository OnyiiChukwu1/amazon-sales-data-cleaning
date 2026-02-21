📌 Project Overview
This project demonstrates a complete data cleaning process on a raw Amazon sales dataset containing inconsistencies, missing values, invalid dates, and mixed data types.
The objective was to transform messy transactional data into a structured, analysis-ready dataset.
Dataset Description

The dataset contains:

Order_ID
Product_Name
Category
Order_Date
Quantity
Unit_Price
Total_Sales
Region
Customer_Rating

The raw data included:
Invalid date formats (e.g., 2023-13-40)
Mixed date styles (DD/MM/YYYY, MM/DD/YY)
Text values in numeric fields (e.g., “two”)
Negative quantities
Blank key fields
Inconsistent category naming

Data Cleaning Process

The following steps were performed:
Standardized category labels (e.g., Electronic → Electronics).
Converted mixed date formats into a consistent ISO format (YYYY-MM-DD).
Removed invalid date entries.
Converted Quantity and Unit_Price columns to numeric format.
Recalculated Total_Sales using: Quantity × Unit_Price
Removed structural misalignment caused by blank cell deletions.
Handled missing values appropriately:Text fields labeled as "Unknown" where applicable.
Numeric/date fields retained as null where data was unavailable.
Preserved dataset integrity by avoiding random value imputation.

Data Validation
Verified numeric columns using type checks.
Recomputed Total_Sales to ensure transactional accuracy.
Confirmed column consistency and formatting.
Reviewed blank Order_ID entries for structural integrity.

Skills Demonstrated
Data Cleaning & Transformation
Handling Missing Data
Data Validation
Error Detection
Excel Functions (IF, ISNUMBER, TEXT, etc.)
Structured Dataset Preparation
Analytical Thinking

Business Value
A clean dataset ensures:Accurate revenue analysis
Reliable monthly sales trends
Correct regional performance comparisons
Trustworthy reporting
Poor data quality leads to incorrect financial insights.

Outcome

The final dataset is structured, validated, and ready for:
Pivot table analysis
Revenue dashboards
Trend analysis
Business intelligence reporting

Files Included
Raw Dataset
Cleaned Dataset
Documentation

Author

Nnaji Onyinye Maryann
Junior Data Analyst | Education & Sales Data Enthusiast
