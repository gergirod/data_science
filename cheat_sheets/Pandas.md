# Pandas Cheat Sheet

[Pandas](http://pandas.pydata.org/) Pandas is arguably the most important Python package for data science. Not only does it give you lots of methods and functions that make working with data easier, but it has been optimized for speed which gives you a significant advantage compared with working with numeric data using Python’s built-in functions.

## Index
1. [Basics](#basics)
2. [Importin/Exporting Data](#importExportingingdata)
    - [Importing Data](#importing)
    - [Exporting Data](#exporting)
3. [Mathematics](#maths)
    - [Arithmetic Operations](#ops)
      * [Examples](#operations-examples)
    - [Comparison](#comparison)
      * [Examples](#comparison-example)
    - [Basic Statistics](#stats)
    - [More](#more)
4. [Slicing and Subsetting](#ss)
    - [Examples](#exp)
5. [Tricks](#tricks)
6. [Credits](#creds)

</br>

## Basics <a name="basics"></a>

`df` Any pandas DataFrame object </br>
`s` Any pandas Series objects
import pandas as pd</br>
import numpy as np

## Importing/Exporting Data <a name="importExportingingdata"></a>

### Importing data <a name="importing"></a>


| Operators | Description |
| :------------- | :------------- |
|`pd.read_csv(filename)`|From a CSV file |
|`pd.read_table(filename)`|From a delimited text file (like TSV)|
|`pd.read_excel(filename)`|From an Excel file|
|`pd.read_sql(query, connection_object)`|Read from a SQL table/database|
|`pd.read_json(json_string)`|Read from a JSON formatted string, URL or file.|
|`pd.read_html(url)	`|Parses an html URL, string or file and extracts tables to a list of dataframes|
|`pd.read_clipboard()`|Takes the contents of your clipboard and passes it to read_table()|
|`pd.DataFrame(dict)`|From a dict, keys for columns names, values for data as lists|

### Exporting data <a name="exporting"></a>


| Operators | Description |
| :------------- | :------------- |
|`df.to_csv(filename)`|Write to a CSV file|
|`df.to_excel(filename)	`|Write to an Excel file|
|`df.to_sql(table_name, connection_object)`|Write to a SQL table|
|`df.to_json(filename)`|Write to a file in JSON format|


