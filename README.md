Task 5 – Exploratory Data Analysis (EDA) on Titanic Dataset

Objective

The objective of this project is to perform Exploratory Data Analysis (EDA) on the Titanic dataset to uncover patterns, trends, and relationships influencing passenger survival.

The analysis focuses on understanding feature distributions, correlations, and key factors affecting survival outcomes.

Dataset Overview

Dataset: Titanic (train.csv)

Total Observations: 891 passengers

Total Features: 12 (before preprocessing)

Target Variable: Survived

0 = Did Not Survive

1 = Survived

Problem Type: Binary Classification

Statistical Highlights

Average Age ≈ 29.7 years

Average Fare ≈ 32.20

Overall Survival Rate ≈ 38%

Tools & Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Google Colab

Steps Performed
1️⃣ Data Understanding

Used .info(), .describe(), and .value_counts()

Checked data types and missing values

2️⃣ Data Cleaning

Filled missing values in Age using mean

Filled missing values in Embarked using mode

Dropped Cabin column due to excessive missing values

Converted categorical variables into numeric format for correlation analysis

3️⃣ Univariate Analysis

Plotted histograms for Age and Fare

Analyzed distribution of Passenger Class, Gender, and Embarkation Port

4️⃣ Bivariate Analysis

Survival vs Gender

Survival vs Passenger Class

Survival vs Fare

Survival vs Age

Correlation Analysis

Created correlation heatmap

Identified relationships between numerical features

Observed multicollinearity patterns
Key Findings

Gender is the strongest survival factor – Females had significantly higher survival rates.

Passenger Class strongly influenced survival – 1st class passengers survived more.

Fare shows positive correlation with survival, indicating socio-economic impact.

Age has weak correlation with survival.

Pclass and Fare are strongly negatively correlated, indicating multicollinearity.

Majority passengers were aged between 20–40 years.

Fare distribution is positively skewed with noticeable outliers.
