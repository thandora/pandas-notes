# Pandas Library Notes
This is my work-in-progress personal notes for the pandas library for Python.  

## Requirements
This notes uses pandas 2.0 library and the 2022 stackoverflow dev survey ([download survey](https://info.stackoverflowsolutions.com/rs/719-EMH-566/images/stack-overflow-developer-survey-2022.zip))

## TODO - in order of priority
- Finish remaining sections (7 onwards)
- welp. pandas docs use indexes for referring to the plural of indices. I used indices. Replace all indices.
- Convert comments to md for pandas_02 and pandas_03

## Table of Contents
How to read: index will refer to the suffix of the .ipynb file.  
(e.g.) **04a** means that the topic is discussed under **pandas_04a.ipynb**  

* **01a - pandas Data Structures**
  * Introduction to pandas' Series and DataFrame
  * How to create a Series and DataFrame
* **01b - Loading Data Set as DataFrame, Viewing DataFrame, and pandas Options**
  * Creating DataFrame from existing data file
  * Viewing DataFrame using .head() and .tail()
  * Setting and resetting pandas options
* **02 - Selecting Rows and Columns of DataFrame**
  * Selecting using indexing and by dot notation.
  * Selecting usings .loc() and .iloc()
* **03 - Index**
  * Using index
  * Setting and resetting index
* **04a - Filtering Data in DataFrame (and series?)**
  * Creating filters
  * Applying filters
* **04b - Filtering Examples on Real Data**
* **05a - Modifying Data in DataFrames and Series**
  * Assigning column labels
  * Updating row and column data