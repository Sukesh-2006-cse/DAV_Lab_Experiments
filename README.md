# README – Pandas Data Analysis and Visualization Lab Programs

## Overview

This repository contains four Python programs that demonstrate fundamental and advanced data analysis techniques using **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**, and **SciPy**. These programs cover data loading, preprocessing, exploratory data analysis (EDA), visualization, and statistical analysis using real-world datasets.

---

# Program 1: Pandas Data Manipulation and Basic Visualization

## Objective

The objective of this program is to understand the basic operations of the Pandas library, including reading datasets, handling missing values, filtering data, sorting, grouping, creating new columns, exporting processed data, and generating simple visualizations.

### Libraries Used

* Pandas
* NumPy
* Matplotlib

### Operations Performed

* Read CSV file
* Display first and last records
* Display dataset information
* Generate descriptive statistics
* Handle missing values
* Create a new column
* Perform Series operations
* Filter rows using conditions
* Group data and calculate mean values
* Sort records
* Apply Boolean masking
* Remove duplicate rows
* Remove missing values
* Create a subset of selected columns
* Export processed data into a CSV file
* Calculate Sum, Mean and Standard Deviation

### Visualizations

* Bar Chart
* Line Chart

### Functions Used

| Function          | Description                   |
| ----------------- | ----------------------------- |
| read_csv()        | Reads CSV dataset             |
| head()            | Displays first five rows      |
| tail()            | Displays last five rows       |
| info()            | Displays dataset information  |
| describe()        | Generates statistical summary |
| fillna()          | Fills missing values          |
| groupby()         | Groups data                   |
| sort_values()     | Sorts data                    |
| drop_duplicates() | Removes duplicate records     |
| dropna()          | Removes missing values        |
| to_csv()          | Saves processed dataset       |

### Learning Outcome

After completing this program, students will be able to:

* Import datasets
* Clean datasets
* Filter and sort data
* Perform aggregation
* Export processed data
* Create basic graphs

---

# Program 2: Importing Data from Multiple Sources

## Objective

This program demonstrates how to import data from different sources such as CSV files, Excel files, and online datasets.

### Libraries Used

* Pandas

### Data Sources

* CSV File
* Excel File
* Online Dataset (GitHub URL)

### Operations Performed

* Read CSV file
* Read Excel file
* Read data from URL
* Display datasets
* Handle missing values using Forward Fill
* Handle missing values using Backward Fill
* Remove missing records
* Save processed CSV file
* Save processed Excel file

### Functions Used

| Function     | Description                   |
| ------------ | ----------------------------- |
| read_csv()   | Reads CSV files               |
| read_excel() | Reads Excel files             |
| ffill()      | Forward fills missing values  |
| bfill()      | Backward fills missing values |
| dropna()     | Removes missing values        |
| to_csv()     | Saves CSV file                |
| to_excel()   | Saves Excel file              |

### Learning Outcome

Students learn how to:

* Import datasets from different formats
* Handle missing values
* Export cleaned datasets
* Work with online datasets

---

# Program 3: Exploratory Data Analysis Using Titanic Dataset

## Objective

The objective of this program is to perform Exploratory Data Analysis (EDA) on the Titanic dataset and understand relationships among different passenger attributes using statistical analysis and visualization.

### Dataset

Titanic Passenger Dataset

### Libraries Used

* Pandas
* Seaborn
* Matplotlib

### Dataset Analysis

The program displays:

* First and last records
* Dataset dimensions
* Column names
* Data types
* Missing values
* Duplicate records
* Statistical summary

### Statistical Analysis

The following analyses are performed:

* Passenger survival count
* Gender distribution
* Passenger class distribution
* Embarked port distribution
* Average fare by passenger class
* Average age by gender
* Average fare based on survival
* Correlation matrix
* Highest fare passengers
* Oldest passengers

### Visualizations

The program generates the following plots:

1. Survival Count Plot
2. Gender Distribution Plot
3. Passenger Class Distribution
4. Age Histogram
5. Fare Histogram
6. Fare Box Plot by Passenger Class
7. Age vs Fare Scatter Plot
8. Age Distribution by Survival (Violin Plot)
9. Average Fare by Passenger Class (Bar Plot)
10. Correlation Heatmap
11. Pair Plot

### Functions Used

| Function      | Description                          |
| ------------- | ------------------------------------ |
| countplot()   | Displays frequency counts            |
| histplot()    | Displays histogram                   |
| boxplot()     | Shows outliers and spread            |
| violinplot()  | Shows density and distribution       |
| scatterplot() | Shows relationship between variables |
| barplot()     | Displays average values              |
| heatmap()     | Displays correlation matrix          |
| pairplot()    | Compares multiple variables          |

### Learning Outcome

Students understand:

* Exploratory Data Analysis
* Feature relationships
* Correlation analysis
* Distribution analysis
* Data visualization techniques

---

# Program 4: Univariate Statistical Analysis Using Pima Indians Diabetes Dataset

## Objective

The objective of this program is to perform univariate statistical analysis on numerical attributes of the Pima Indians Diabetes dataset.

### Dataset

Pima Indians Diabetes Dataset

### Libraries Used

* Pandas
* NumPy
* SciPy

### Numerical Features

* Glucose
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Diabetes Pedigree Function
* Age

### Statistical Measures Calculated

* Mean
* Median
* Mode
* Minimum
* Maximum
* Range
* Variance
* Standard Deviation
* Skewness
* Kurtosis

### Additional Analysis

* Outcome distribution
* Correlation matrix

### Statistical Terms

**Mean**

Average value of the dataset.

**Median**

Middle value after arranging the observations.

**Mode**

Most frequently occurring value.

**Variance**

Measures how much the data varies from the mean.

**Standard Deviation**

Measures the spread of observations around the mean.

**Skewness**

Measures the symmetry of the distribution.

* Positive → Right-skewed
* Negative → Left-skewed
* Zero → Symmetric

**Kurtosis**

Measures the peakedness of the distribution.

* Positive → Heavy tails
* Negative → Light tails
* Zero → Normal distribution

### Learning Outcome

Students learn:

* Descriptive statistics
* Statistical analysis
* Healthcare data analysis
* Data interpretation
* Correlation analysis

---

# Libraries Used

| Library    | Purpose                            |
| ---------- | ---------------------------------- |
| Pandas     | Data manipulation and analysis     |
| NumPy      | Numerical computations             |
| Matplotlib | Basic plotting                     |
| Seaborn    | Advanced statistical visualization |
| SciPy      | Statistical calculations           |

---

# Common Pandas Functions

| Function          | Purpose                  |
| ----------------- | ------------------------ |
| read_csv()        | Import CSV file          |
| read_excel()      | Import Excel file        |
| head()            | Display first records    |
| tail()            | Display last records     |
| info()            | Dataset information      |
| describe()        | Statistical summary      |
| groupby()         | Group data               |
| sort_values()     | Sort records             |
| fillna()          | Fill missing values      |
| dropna()          | Remove missing values    |
| drop_duplicates() | Remove duplicate records |
| value_counts()    | Frequency count          |
| corr()            | Correlation matrix       |
| to_csv()          | Export CSV               |
| to_excel()        | Export Excel             |

---

# Visualization Techniques

| Visualization | Purpose                                                   |
| ------------- | --------------------------------------------------------- |
| Histogram     | Displays numerical data distribution                      |
| Bar Plot      | Compares categories                                       |
| Count Plot    | Shows frequency of categories                             |
| Scatter Plot  | Shows relationship between numerical variables            |
| Box Plot      | Detects outliers and spread                               |
| Violin Plot   | Shows density and distribution                            |
| Heatmap       | Displays correlation matrix                               |
| Pair Plot     | Compares relationships among multiple numerical variables |

---

# Overall Learning Outcomes

By completing these four programs, students will be able to:

* Import datasets from CSV, Excel, and online sources.
* Clean and preprocess datasets.
* Handle missing values and duplicate records.
* Perform descriptive statistical analysis.
* Filter, sort, group, and aggregate data using Pandas.
* Export processed datasets into CSV and Excel formats.
* Perform Exploratory Data Analysis (EDA) on real-world datasets.
* Generate professional visualizations using Matplotlib and Seaborn.
* Interpret statistical measures such as mean, median, mode, variance, standard deviation, skewness, and kurtosis.
* Analyze relationships among variables using correlation matrices, scatter plots, heatmaps, and pair plots.
* Apply data analysis techniques to business, healthcare, finance, research, and machine learning datasets.
