# Pandas Library Notes

This is my personal notes for the pandas library for Python based on Corey Schafer's [pandas playlist](https://www.youtube.com/watch?v=ZyhVh-qRZPA&list=PL-osiE80TeTsWmV9i9c58mdDCSskIFdDS). These notes are upto date (not using deprecated functions used on the playlist), and is using the new pandas 2.0.0 released on April 3, 2023.  

First finished version completed on May 12, 2023.

## Requirements

This notes uses pandas 2.0.0 library and various data sets, which are included except for the 2022 stackoverflow dev survey ([download survey](https://info.stackoverflowsolutions.com/rs/719-EMH-566/images/stack-overflow-developer-survey-2022.zip)).

**To install pandas:**  
`pip install pandas==2.0.0`

**Stackoverflow Developer Survey:**  
Place inside the *data* folder

## Data Sets

### Stackoverflow Developer Survey (Not included)

Used on all chapters except chapter 10 - [Stackoverflow](https://info.stackoverflowsolutions.com/rs/719-EMH-566/imagesstack-overflow-developer-survey-2022.zip)  

### Etherium time series data (Included)

Used on chapter 10 - [Corey Schafer](https://github.com/CoreyMSchafer/code_snippets/tree/master/Python/Pandas/10-Datetime-Timeseries)  

### Excel sample files (Included)

Used on chapter 11 - [file-examples.com](https://file-examples.com/index.php/sample-documents-download/sample-xls-download/)

### SQLite sample file (Included)

Used on chapter 11

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
  - Setting and resetting index
  - Using index
- **04a - Filtering Data in DataFrame (and series?)**
  - Creating filters
    - Using .isin()
    - Using .contains()
  - Applying filters
  - Filter with multiple conditions using &
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
- **10 - Dates and Time Series Data**
  - Converting to datetime object
  - Loading as datetime object
  - Datetime Operations
    - Datetime and datetime Series methods
    - Difference between comparators in filtering
  - Timedelta Type and Operations
    - Difference between datetimes
    - Filtering dates
  - Resampling
    - Resampling a single column
    - Resampling multiple columns with different functions
- **11 - Reading and Writing Data to Different Sources**
  - Comma Separated Values (CSV)
    - Delimiters and other separated values
  - Excel files (XLSX and XLS)
    - Dependencies
    - Excel worksheets
  - JavaScript Notation Object (JSON)
    - pandas JSON Orientation
  - Databases (SQLite)
    - Reading SQL Database
    - Writing to SQL Database
