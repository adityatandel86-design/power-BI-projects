Data Leverager – Power Query Transformation Project

Project Overview

Data Leverager is a Power BI ETL project focused on data extraction, cleaning, transformation, integration, and preparation using Power Query. The project simulates real-world data engineering workflows by combining multiple data sources and applying various transformation techniques without using DAX or visualizations.

---

Objective

The objective of this project is to perform end-to-end ETL operations in Power BI using Power Query, including data cleaning, reshaping, merging, appending, aggregation, and data quality analysis.

---

Tools Used

- Power BI Desktop
- Power Query Editor
- Microsoft Excel
- Web Data Source (HTML Table)

---

Data Sources

1. Sales_Jan.xlsx
2. Sales_Feb.xlsx
3. Sales_Mar.xlsx
4. Employee Dataset
5. HTML Table from Web Source

---

Transformations Performed

Data Cleaning

- Removed blank rows and columns
- Promoted first row as headers
- Renamed columns
- Changed data types
- Removed duplicates
- Filtered null values

Text Transformations

- Applied UPPER()
- Applied LOWER()
- Applied TRIM()
- Applied CLEAN()
- Replaced unwanted text
- Split columns using delimiters

Numeric Transformations

- Rounded revenue values
- Created Profit column (Revenue - Cost)

Date Transformations

- Extracted Day, Month, Year, and Quarter
- Created Fiscal Month column
- Calculated Age from Birthdate

Conditional Logic & Indexing

- Created Sales Category column
- Added 0-based Index
- Added 1-based Index

Data Integration

- Merged Sales and Employee datasets
- Appended monthly sales files

Aggregation

- Total Sales by Region
- Average Order Value
- Transaction Count

Data Quality Analysis

- Column Profile
- Column Distribution
- Column Quality

---

Screenshots

Employee Data Cleaning

"Employee Data" (step1.png.png)

Merge Queries

"Merge Queries" (step2.png.png)

Append Queries

"Append Queries" (step3.png.png)

---

Challenges Faced

- Handling inconsistent data formats
- Managing null and duplicate values
- Merging datasets with matching keys
- Maintaining transformation steps during refresh

---

Solution

These challenges were resolved using Power Query transformation tools, proper data type management, data profiling features, and structured ETL processes.

---

Project Outcome

Successfully created a clean, transformed, and integrated dataset using Power Query. All ETL requirements were completed while maintaining data quality and refresh compatibility.

---

Author

Aditya Tandel
Power BI ETL Project – Data Leverager
