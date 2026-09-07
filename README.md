Global Tech Job Market & Career Trajectories (2019–2026)
#Project Overview

This project performs Exploratory Data Analysis (EDA) on a global technology job market dataset containing 115,000 job postings from 2019 to August 2026.

The main objective is to understand patterns in the tech job market and identify important relationships between factors such as job roles, sectors, salary, work mode, experience requirements, hiring process, and job outcomes.

The project also focuses on identifying and handling data-quality issues present in the dataset.

#Dataset
Rows: 115,000
Columns: 28
Time Period: January 2019 – August 2026
Unit of Analysis: One row represents one job posting

The dataset contains information about:

Company and company type
Industry sector
Company size
Job role and seniority
Required experience
Required technology stack
Programming language
Work mode
Visa sponsorship
Job location
Salary range
Posting and filling dates
Number of applicants
Interview rounds
Offers extended and accepted
Position status
Layoff indicator
#EDA Performed

The analysis includes:

Dataset structure and data types
Missing-value analysis
Duplicate analysis
Categorical value consistency
Logical and referential checks
Numerical distributions and outlier analysis
Univariate analysis
Bivariate analysis
Multivariate analysis
Time-based analysis
Feature engineering
#Feature Engineering

The following features were created:

avg_salary – average of minimum and maximum salary
time_to_fill_days – number of days between posting and position-filled date
offer_accept_ratio – accepted offers divided by extended offers


#Data Quality Handling

Important data-quality issues identified during EDA include:

Missing values
Exact duplicate records
Mixed salary formats
Placeholder values such as -1
Inconsistent categorical labels
Date columns stored in non-datetime format
Logical inconsistencies checked between related columns

These issues were investigated and appropriate transformations were applied where required.

#Key Areas of Analysis

The project analyzes relationships such as:

Salary vs. work mode
Salary vs. seniority level
Salary vs. sector
Applicants vs. work mode
Applicants vs. seniority
Interview rounds vs. position status
Visa sponsorship vs. work mode
Experience requirements vs. salary
Job market trends over time
Technology requirements across job postings
#Tools & Libraries
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook / Google Colab
#Project Structure
Global-Tech-Job-Market-EDA/
│
├── Global_Tech_Job_Market_EDA.ipynb
├── README.md
├── .gitignore
└── requirements.txt


Vaishnavi