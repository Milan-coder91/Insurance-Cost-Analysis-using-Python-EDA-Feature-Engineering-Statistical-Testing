# Insurance Cost Analysis using Python

## Project Overview
This project focuses on analyzing an insurance dataset to understand the factors affecting medical insurance charges. The analysis includes data cleaning, exploratory data analysis (EDA), feature engineering, statistical testing, and data preprocessing for machine learning.

## Objective
The main goal of this project is to identify key factors that influence insurance charges, such as age, BMI, smoking habits, number of children, and region.

## Dataset Information
The dataset contains the following features:
- **age**: Age of the individual
- **sex**: Gender of the individual
- **bmi**: Body Mass Index
- **children**: Number of dependents
- **smoker**: Smoking status
- **region**: Residential region
- **charges**: Medical insurance charges

## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

## Project Workflow

### 1. Data Cleaning
- Checked dataset shape and structure
- Removed duplicate records
- Checked and handled missing values
- Corrected data types

### 2. Exploratory Data Analysis (EDA)
- Distribution analysis of numerical features
- Outlier detection using boxplots
- Correlation analysis
- Categorical feature analysis

### 3. Feature Engineering
- Converted categorical columns (`sex`, `smoker`) into numerical values
- Created a new feature: **BMI Category**
- Applied one-hot encoding on the `region` column

### 4. Data Preprocessing
- Standardized numerical features using **StandardScaler**

### 5. Statistical Analysis
- Pearson correlation test
- Chi-square test for categorical relationships

## Key Insights
- Smoking status has a significant impact on insurance charges.
- Higher BMI is associated with increased medical costs.
- Age positively correlates with insurance charges.
- Regional differences have limited impact compared to lifestyle factors.

## Project Files
- `insurance.ipynb` → Jupyter Notebook with complete analysis
- `insurance.csv` → Dataset
- `README.md` → Project documentation

## Conclusion
This project demonstrates practical skills in data cleaning, exploratory analysis, feature engineering, and preprocessing. It provides valuable insights into healthcare insurance pricing and serves as a foundation for predictive modeling.

## Author
**Milan Kumar**
Aspiring Data Analyst
