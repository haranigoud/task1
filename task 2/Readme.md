Task 1: Understanding Dataset & Data Types

AI & ML Internship

 Objective :

The objective of this task is to understand the structure, data types, and machine learning readiness of datasets by performing exploratory data analysis (EDA) using Python and Pandas.

This task focuses on:

Understanding different types of data
Identifying target and input features
Checking data quality issues such as missing values
Detecting class imbalance
Assessing dataset suitability for machine learning

 Tools & Technologies Used :

Python
Pandas
jupyter Notebook / Google Colab

 Datasets Used :
 Titanic Dataset (train.csv) :

Contains passenger details such as age, gender, ticket class, fare, and survival status.

 Students Performance Dataset (StudentsPerformance.csv) :

Contains students’ academic performance data along with demographic and socio-economic factors.

Task Description :

The following steps were performed on both datasets:

 Load the Dataset :

Loaded using pandas.read_csv()
Displayed the first and last 5 rows to understand dataset structure

 Identify Feature Types :

Columns were manually classified into different data types.

 Numerical Data :

Titanic: PassengerId, Survived, Age, SibSp, Parch, Fare
Students: math score, reading score, writing score

 Categorical Data :

Titanic: Sex, Ticket, Cabin, Embarked
Students: gender, race/ethnicity, parental level of education, lunch, test preparation course

 Ordinal Data :

Titanic: Pclass
Students: parental level of education

 Binary Data :

Titanic: Sex, Survived
Students: gender, lunch, test preparation course
Each category was displayed separately to clearly understand the data types and values.

Dataset Information :

A dataset information table was created for both datasets showing:
Column names
Non-null value counts
Data types
This helped identify missing values and data quality issues.

Statistical Summary :

Used df.describe(include="all")
Provided statistical insights such as mean, standard deviation, minimum, maximum, and frequency counts
attach

 Unique Values Analysis  :

Calculated unique value counts for categorical columns
Helped understand category distributions and diversity

 Target Variable Identification :

Titanic Dataset: Survived
Students Performance Dataset: math score
All remaining columns were treated as input features.

 Dataset Size Analysis :

Total number of rows and columns were calculated
Both datasets are of reasonable size and suitable for machine learning

 Missing Values Analysis :

Titanic dataset contains missing values in Age, Cabin, and Embarked
Students Performance dataset contains no missing values

 Target Variable Distribution :

Titanic dataset shows class imbalance in the Survived variable
Students dataset shows a well-distributed numerical target variable (math score)

 Observations & Insights :

Titanic dataset requires preprocessing due to missing values and class imbalance
Students Performance dataset is clean and ready for modeling
Both datasets are suitable for machine learning after appropriate preprocessing
Understanding data types and quality is essential before building ML models

 Final Outcome :

By completing this task:

I gained hands-on experience in exploratory data analysis
Learned to classify numerical, categorical, ordinal, and binary data
Understood how to detect missing values and imbalance
Learned how to assess ML readiness of datasets