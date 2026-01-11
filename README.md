# Notes

This repository contains several practice projects using Python Pandas.

- [Notes](#notes)
  - [Data Cleaning with Pandas](#data-cleaning-with-pandas)
  - [Pandas `groupby` Function Using Seaborn datasets](#pandas-groupby-function-using-seaborn-datasets)
  - [Sorting Data in Pandas](#sorting-data-in-pandas)
  - [Pandas `replace`](#pandas-replace)
  - [Pandas `rolling`](#pandas-rolling)
  - [Pandas `where`](#pandas-where)

---

## Data Cleaning with Pandas

The project file is [pandas_data_cleaning.ipynb](./pandas_data_cleaning.ipynb)

This project performs data cleaning and exploratory analysis on cricket match statistics. The analysis includes:

- Renaming columns for clarity (Mat → Matches, NO → Not_Outs, etc.)
- Handling missing values
- Removing duplicate entries
- Extracting player names and country codes from combined fields
- Parsing year ranges into separate columns
- Converting data types and removing special characters (+, \*) from numeric fields

The project could be coded along following this link:  
[Real World Data Cleaning in Python Pandas (Step By Step)](https://www.youtube.com/watch?v=iaZQF8SLHJs)

---

## Pandas `groupby` Function Using Seaborn datasets

This Jupyter notebook is a comprehensive pandas `groupby` operations tutorial that demonstrates various data aggregation and transformation techniques using two datasets from the Seaborn library: the "tips" dataset (restaurant tipping data) and the "taxis" dataset (NYC taxi ride data).

The project file is [pandas_groupby.ipynb](./pandas_groupby.ipynb)

Key topics covered:

- **Basic aggregations**: `mean()`, `median()`, `sum()`, `count()`, `min()`, `max()`, `nunique()`
- **Multiple aggregations**: Using `agg()` with lists and custom column names
- **Multi-level grouping**: Grouping by multiple columns simultaneously
- **Statistical summaries**: `describe()` and quantile calculations
- **Transform operations**: Adding group-level statistics back to the original dataframe (e.g., median bill per time period, z-scores)
- **Custom functions**: Using `apply()` with lambda functions for complex calculations (e.g., average tip percentage)
- **DateTime operations**: Grouping by date components (month extraction)
- **Interquartile range calculations**: Computing Q1, Q3, and IQR for different groups

The project could be coded along following this link:  
[The Complete Guide to Python Pandas Groupby](https://www.youtube.com/watch?v=L5kf4sQnVhI)

---

## Sorting Data in Pandas

This Jupyter notebook demonstrates comprehensive sorting techniques in pandas.

The project file is [pandas_sorting.ipynb](./pandas_sorting.ipynb)

Key topics covered:

- **Basic sorting**: Series and DataFrame sorting with `sort_values()` (ascending/descending)
- **Multi-column sorting**: Sorting by multiple columns with different sort orders
- **Handling missing data**: Using `na_position` parameter to control NaN placement
- **Index sorting**: Sorting by index with `sort_index()`, including date-based indices
- **Custom sorting**: Using the `key` parameter with lambda functions for custom sort logic
- **Top/bottom selection**: Using `nlargest()` and `nsmallest()` for efficient retrieval of extreme values

The project could be coded along following this link:  
[How to Sort Data in Python Pandas](https://www.youtube.com/watch?v=VcwxUet5a3k)

---

## Pandas `replace`

The notebook covers seven practical examples of using pandas' `replace()` method.

The project file is [pandas_replace.ipynb](./pandas_replace.ipynb)

Key topics covered:

- **Single value replacement**: Replace one specific value in a column
- **Multiple values to one**: Replace several values with a single value
- **Dictionary mapping**: Replace multiple values with multiple values using a dictionary
- **List-based replacement**: Replace multiple values with multiple values using a list
- **Entire DataFrame replacement**: Apply replacements across all columns at once
- **Regex pattern matching**: Use regular expressions to find and replace partial text patterns

The project could be coded along following this link:  
[Clean Your Data FAST with Pandas replace()](https://www.youtube.com/watch?v=uMuyRonKMk4)

---

## Pandas `rolling`

This Jupyter notebook demonstrates pandas `rolling` window functions with examples using venue data (capacity and ticket sales).

The project file is [pandas_rolling.ipynb](./pandas_rolling.ipynb)

Key topics covered:

- **Basic rolling operations**: `mean()`, `sum()`, `min()`, and `max()` across a 3-5 row window
- **Multiple column aggregation**: calculating rolling statistics on different columns simultaneously
- **Custom functions**: using `.apply()` for custom rolling calculations
- **Grouped rolling windows**: computing rolling averages within specific groups (by venue)
- **Advanced techniques**:
  - `.shift()` to compare current values against previous rolling averages
  - `.ffill()` for forward-filling missing values before rolling calculations

The project could be coded along following this link:  
[12 Practical Pandas Rolling Examples](https://www.youtube.com/watch?v=-YfPCxZ2TFE)

---

## Pandas `where`

This notebook demonstrates various use cases of the pandas `.where()` method for conditional data filtering and replacement.

The project file is [pandas_where.ipynb](./pandas_where.ipynb)

Key topics covered:

- **Basic filtering**: Keeping values that meet conditions, replacing others with NaN
- **Value replacement**: Using the `other` parameter to replace filtered values with specific alternatives
- **Null handling**: Filling null values conditionally
- **Column-based conditions**: Filtering entire dataframes based on single column criteria
- **Complex conditions**: Combining multiple conditions using `&` (AND) and `|` (OR) operators
- **Column creation**: Generating new columns with conditional values

The project could be coded along following this link:  
[Pandas where() Explained with Multiple Examples](https://www.youtube.com/watch?v=Y7HMkDuR_DA)
