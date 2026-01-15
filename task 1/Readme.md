Task 1: Understanding Dataset & Data Types

AI & ML Internship

 Objective :

The objective of this task is to understand the structure, data types, and machine learning readiness of the Titanic Dataset by performing exploratory data analysis using Python and Pandas.

This task focuses on:

Understanding different types of data

Identifying target and input features

Checking data quality issues such as missing values and imbalance

Tools & Technologies Used :

Python

Pandas

Jupyter Notebook / Google Colab

 Dataset Used :

Titanic Dataset (train.csv)

The dataset contains passenger details such as age, gender, ticket class, fare, and survival status.

Task Description :

The following steps were performed in this task:

 Load the Dataset :

The dataset is loaded using pandas.read_csv()

First and last 5 rows are displayed to understand the structure of the data

 Identify Feature Types :

Columns are manually classified into:

Numerical Columns
PassengerId, Survived, Pclass, Age, SibSp, Parch, Fare

Categorical Columns
Sex, Ticket, Cabin, Embarked

Ordinal Columns
Pclass

Binary Columns
Sex, Survived

Each category is displayed separately to clearly understand the data types.
 
 Dataset Information :

A custom dataset info table is created showing:

Column names

Non-null value counts

Data types

This helps identify missing values and understand column data types clearly.

 Statistical Summary :

df.describe(include="all") is used to generate statistical summaries for both numerical and categorical features.

This provides insights such as mean, standard deviation, min/max values, and frequency counts.

 Unique Values Analysis :

Unique value counts are calculated for categorical columns to understand data distribution and variety.

 Target Variable Identification :

Target Variable: Survived

Input Features: All remaining columns except Survived

This step prepares the dataset for future machine learning models.

Dataset Size Analysis :

Number of rows and columns are calculated

Helps evaluate whether the dataset is suitable for machine learning

Missing Values Analysis :

Missing values are calculated for each column

Identifies data quality issues that need preprocessing

 Target Variable Distribution :

Survival count is displayed

Helps detect class imbalance, which is important for ML model performance

 Observations & Insights :

The dataset contains missing values in columns like Age, Cabin, and Embarked

Cabin has a large number of missing values

The target variable Survived shows class imbalance

The dataset is of reasonable size and suitable for machine learning after preprocessing
