# Pandas Library Notes

This is my work-in-progress personal notes for the pandas library for Python.  

## Requirements

This notes uses pandas 2.0 library and the 2022 stackoverflow dev survey ([download survey](https://info.stackoverflowsolutions.com/rs/719-EMH-566/images/stack-overflow-developer-survey-2022.zip)).  
To install pandas:  
`pip install pandas==2.0.0`

## TODO - in order of priority

- Finish remaining sections (9 onwards)
- Convert comments to md for pandas_02 and pandas_03
- Add example for adding columns using .concat and adding rows using indexing for pandas_06.

## Table of Contents

How to read: index will refer to the suffix of the .ipynb file.  
(e.g.) **04a** means that the topic is discussed under **pandas_04a.ipynb**  

- **01a - pandas Data Structures**
  - Introduction to pandas' Series and DataFrame
  - How to create a Series and DataFrame
- **01b - Loading Data Set as DataFrame, Viewing DataFrame, and pandas Options**
  - Creating DataFrame from existing data file
  - Viewing DataFrame using .head() and .tail()
  - Setting and resetting pandas options
- **02 - Selecting Rows and Columns of DataFrame**
  - Selecting using indexing and by dot notation.
  - Selecting usings .loc() and .iloc()
- **03 - Index**
  - Using index
  - Setting and resetting index
- **04a - Filtering Data in DataFrame (and series?)**
  - Creating filters
    - Using .isin()
    - Using .contains()
  - Applying filters
- **04b - Filtering Examples on Real Data**
- **05a - Modifying Data in DataFrames and Series**
  - Assigning column labels
  - Updating row and column data
- **06 - Adding and Removing Columns and Rows**
  - Adding columns and rows
    - Using indexing
    - Using .concat()
  - Removing columns and rows
    - Using .drop()
- **07a - Sorting Data**
  - Sorting single column or row using .sort_values()
  - Sorting multiple columns or rows using .sort_values()
  - Sorting using .nlargest() and .nsmallest()
- **07b - Sorting Examples on Real Data**
- **08 - Grouping and Aggregating Data**
  - Aggregating data
    - Using .describe()
    - Using .value_counts()
    - Using other methods
  - Grouping Data
    - groupby objects
    - Applying methods on groupby objects
    - Grouping functions using the .aggregate() method
  - Examples on exploring data
- **09a - Cleaning and Handling Missing Values**
  - What are missing values?
  - Handling missing values
    - By deletion - using .dropna()
    - By imputation - using .fillna()
  - Handling custom null values using .replace()
  - Converting data type using .astype()
  - Viewing dropped values using filters
- **09b - Handling Missing Values on Real Data**
