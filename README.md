# Task 2: Exploratory Data Analysis (EDA)

## Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using Python. The objective is to understand the dataset through descriptive statistics, visualizations, pattern recognition, and outlier detection.

## Objective

- Understand the structure of the dataset
- Generate descriptive statistics
- Identify missing values
- Analyze numerical feature distributions
- Detect potential outliers
- Study relationships between numerical features
- Identify patterns and trends in the data

## Dataset

The Titanic dataset contains information about 891 passengers with 12 features.

Main features include:

- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## EDA Performed

### 1. Dataset Inspection
- Checked dataset shape
- Checked data types
- Inspected the first few rows
- Checked missing values

### 2. Descriptive Statistics
Used `describe()` to calculate:
- Mean
- Standard deviation
- Minimum
- Maximum
- Quartiles

### 3. Data Visualization
Created:
- Histograms
- Boxplots
- Correlation heatmap
- Pairplot

### 4. Survival Analysis
Analyzed survival rates based on:
- Gender
- Passenger class

### 5. Outlier Detection
Used the Interquartile Range (IQR) method to identify potential outliers in Age and Fare.

## Key Findings

- The dataset contains 891 rows and 12 columns.
- Age has 177 missing values.
- Cabin has 687 missing values.
- Embarked has 2 missing values.
- Passenger class has a clear relationship with survival.
- The survival rate for 1st class passengers is approximately 62.96%.
- The survival rate for 2nd class passengers is approximately 47.28%.
- The survival rate for 3rd class passengers is approximately 24.24%.
- 11 potential outliers were detected in Age.
- 116 potential outliers were detected in Fare.
- Visualizations helped identify distributions, relationships, and potential anomalies in the dataset.

## Conclusion

Exploratory Data Analysis helped in understanding the Titanic dataset using statistics and visualizations. Histograms showed the distribution of numerical features, boxplots helped identify potential outliers, and the correlation matrix and pairplot helped understand relationships between numerical features. The analysis also highlighted missing values and important survival patterns.

## Project Structure

```text
Task-2-EDA/
│
├── data/
│   └── Titanic-Dataset.csv
│
├── task-2.ipynb
│
└── README.md