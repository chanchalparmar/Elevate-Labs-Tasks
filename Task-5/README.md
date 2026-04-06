# Elevate Labs Internship Task 5 – Exploratory Data Analysis(EDA)
This repository contains an exploratory data analysis (EDA) notebook titled Exercise 1.ipynb focused on *Alphabet Inc. stock price data. The notebook performs **univariate and bivariate analysis*, visualizations, and time series exploration using Python's data analysis libraries.

## Dataset
The analysis uses a CSV file named alphabet_stock_data.csv, which includes historical stock data with columns such as:
- Date
- Open
- High
- Low
- Close
- Volume

## Key Libraries Used

- pandas
- numpy
- matplotlib
- seaborn

## Analysis Overview

### 1. *Data Loading and Basic Exploration*
- Data is loaded using pandas.read_csv().
- Basic structure explored using .info(), .describe(), .shape, .columns, etc.
- Verified missing/null values and data types.

### 2. *Univariate Analysis*
- *Histograms* to understand the distribution of features like High, Low, Volume.
- *Boxplots* to detect outliers in price data.

### 3. *Bivariate Analysis*
- *Scatter plots* to visualize relationships between stock prices like Open vs Close, High vs Low.
- *Correlation matrix and heatmap* to identify feature correlations.
- *Seaborn Pairplot* to explore pairwise feature relationships.
