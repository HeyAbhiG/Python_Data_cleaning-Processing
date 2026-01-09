# Python_Data_cleaning-Processing
## Objective:
## In this repository i have shown how we can handle :
•	Duplicates
•	Incorrect data types
•	Inconsistent formatting
•	Outliers
•	Typographical or human errors
Before any analysis or visualization, you must clean and prepare this data so that your results are accurate and reliable.


## The Data Cleaning Process (Step-by-Step) :

### Before cleaning, you need to understand your data:
•	How many rows and columns are there?
•	What type of data do you have in each column (numeric, categorical, datetime, text)?
•	What do missing values or anomalies look like?
•	Are there any obvious duplicates or format inconsistencies?

## Techniques:
•	Checking Data types and null value counts
•	Summary statistics (mean, median, min, max)
•	Distribution plots for numerical data
•	Frequency counts for categorical data
•	Visual inspection (head/tail of dataset)

## Handling Missing Values:
•	Delete Rows/Columns: If too much data is missing or unimportant.
•	Imputation (Filling values):
○	Mean/Median/Mode for numeric columns 
○	Mode/ Unknown for categorical
○	Forward/Backward fill for time series
○	Predictive imputation using ML models


## Step 5: Correcting Data Types 
In real-world datasets:
•	Names may have inconsistent casing (e.g., "India", "india", "INDIA") or spelling errors (e.g., "Male", "male ", "M")
•	Dates may have different formats
•	Currencies may vary
•	Extra spaces or typos in categorical fields


## Fixes Like:
•	Standardize casing (lowercase, title-case)
•	Unify date and time formats
•	Trim whitespace/extra space
•	Replace symbols or unwanted characters


## Step 5: Handling Duplicates values:
•	Identify exact duplicates.
•	Check for near-duplicates (same name, different spelling).
•	Remove or consolidate them


## Step 5: Correcting Data Types
## Each column must have the correct data type:
•	Numeric → Integer/Float
•	Text → String/Object
•	Dates → Datetime format
•	Boolean → True/False

## Step 6: Handling Outliers
### Types extra 0
•	Errors (e.g., extra zero: 50000 instead of 5000)

## Handling Techniques:
•	Remove extreme outliers with Statistical methods (Z-score, IQR)
•	Domain knowledge (is that value possible?)
•	Transform data (log/sqrt)
