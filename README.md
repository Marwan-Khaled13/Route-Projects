# Route-Projects
Global Mega Sales – Data Cleaning Project
This project focuses on cleaning and transforming a messy 10,000 rows of sales dataset using Excel and Power Query. The goal was to prepare the data for accurate reporting and analysis.

# Project Goals
Clean invalid email addresses

Fill missing values in UnitPrice, Quantity, and Total

Handle missing or unknown CustomerName, DeliveryStatus, and PaymentMethod

Ensure data consistency for further analysis

# Tools Used
Microsoft Excel

Power Query (M Language)

Excel Formulas (IF, ISBLANK, MODE, FILTER, etc.)

# Cleaning Steps
Email validation: Removed/standardized invalid emails

Calculated missing totals: Total = UnitPrice × Quantity

Back-calculated UnitPrice/Quantity if one was missing

Filled nulls in categorical columns with "Unknown"

Replaced numeric nulls with 0 where appropriate

Verified data using filters and conditional formatting

# Files in this Repo
global_mega_sales_hell_version.csv: Raw data

cleaned_sales_data.xlsx: Cleaned version

data_cleaning_script.txt: Power Query or Excel logic (optional)

README.md: Project documentation

# What You’ll Learn
How to use Excel and Power Query for real-world data cleaning

How to write conditional logic to repair broken datasets

How to make raw data ready for dashboards or modeling
