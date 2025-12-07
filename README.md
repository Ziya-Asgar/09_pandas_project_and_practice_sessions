# Notes

This repository contains several practice projects using Python Pandas.

- [Notes](#notes)
  - [Data Cleaning with Pandas.](#data-cleaning-with-pandas)
  - [Exploratory Data Analysis with Pandas.](#exploratory-data-analysis-with-pandas)
  - [Pandas `groupby` Function Using Seaborn datasets.](#pandas-groupby-function-using-seaborn-datasets)
  - [Sorting Data in Pandas.](#sorting-data-in-pandas)
  - [Pandas `replace`.](#pandas-replace)
  - [Pandas `rolling`](#pandas-rolling)
  - [Pandas `where`](#pandas-where)

---

## Data Cleaning with Pandas.

The project file is [pandas_data_cleaning.ipynb](https://github.com/Ziya-Asgar/09_pandas_project_and_practice_sessions/blob/main/pandas_data_cleaning.ipynb)

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

## Exploratory Data Analysis with Pandas.

This project analyzes two centuries of ultramarathon race data, focusing specifically on 50km and 50-mile races in the USA during 2020.

The project file is [pandas_data_cleaning.ipynb](https://github.com/Ziya-Asgar/09_pandas_project_and_practice_sessions/blob/main/pandas_EDA.ipynb)

- **Data Loading & Cleaning**: Imports a large dataset (7.4M+ rows) of ultramarathon races and filters it down to relevant races
- **Data Filtering**: Extracts races that are:
  - 50km or 50-mile distances
  - Held in the USA
  - Took place in 2020
- **Data Transformation**:
  - Removes country codes from event names
  - Calculates athlete ages
  - Cleans performance times
  - Removes null values
  - Standardizes column names
- **Final Dataset**: Produces a cleaned dataset of 25,857 race results with key metrics including:
  - Race details (date, name, length, finishers)
  - Athlete information (ID, gender, age)
  - Performance metrics (time, average speed)
- **Visualization**: Includes basic exploratory analysis with distribution plots of race lengths

The project could be coded along following this link:  
[Data Analyst Portfolio Project (Exploratory Data Analysis With Python Pandas)](https://www.youtube.com/watch?v=4sZFkPw87ng)

---

## Pandas `groupby` Function Using Seaborn datasets.

This Jupyter notebook is a comprehensive pandas `groupby` operations tutorial that demonstrates various data aggregation and transformation techniques using two datasets from the Seaborn library: the "tips" dataset (restaurant tipping data) and the "taxis" dataset (NYC taxi ride data).

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

## Sorting Data in Pandas.

The project could be coded along following this link:  
[How to Sort Data in Python Pandas](https://www.youtube.com/watch?v=VcwxUet5a3k)

---

## Pandas `replace`.

The project could be coded along following this link:  
[Clean Your Data FAST with Pandas replace()](https://www.youtube.com/watch?v=uMuyRonKMk4)

---

## Pandas `rolling`

The project could be coded along following this link:  
[12 Practical Pandas Rolling Examples](https://www.youtube.com/watch?v=-YfPCxZ2TFE)

---

## Pandas `where`

The project could be coded along following this link:  
[Pandas where() Explained with Multiple Examples](https://www.youtube.com/watch?v=Y7HMkDuR_DA)
