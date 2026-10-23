Data Cleaning and Preparation — SWYNEX Internship Task 1

Project Overview

This project was completed as part of the SWYNEX Technologies Data Analyst Internship. The objective was to clean and prepare a public Titanic passenger dataset for analysis using Python.

Dataset Source

"Public Titanic dataset (CSV)" (https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)

The dataset contains passenger details, including age, passenger class, sex, fare, ticket, and survival status.

Tools Used

- Python
- Pandas
- NumPy
- VS Code
- Jupyter Notebook

Data Cleaning Steps

1. Inspected the dataset structure and data types.
2. Checked for missing values and duplicate records.
3. Removed exact duplicate rows.
4. Removed extra spaces from text values.
5. Standardized categorical values.
6. Converted numerical columns to appropriate data types.
7. Replaced impossible negative values in selected numeric columns with missing values.
8. Filled missing ages using group medians, with an overall median fallback.
9. Filled missing embarkation ports using the mode.
10. Filled missing fares using the median.
11. Removed the Cabin column because it contained many missing values.

Final Results

- Original dataset: 891 rows and 12 columns.
- Cleaned dataset: 891 rows and 11 columns.
- Missing values in the cleaned dataset: 0.
- Exact duplicate rows remaining: 0.
- "SibSp" and "Parch" were converted to integer data types.

Output File

The cleaned dataset is saved as "data/titanic_cleaned.csv".

The Jupyter Notebook contains the data inspection, cleaning code, and verification steps.

Learning Outcomes

This project provided practical experience in data inspection, handling missing values, duplicate detection, data-type conversion, standardizing text values, and exporting cleaned data.