# Exploratory Data Analysis With Python

## Overview

This project performs an in-depth exploratory data analysis (EDA) on Diabetes dataset to uncover insights and visualize key trends. The dataset contains information on the age, glucose levels, BMI, bloodpressure and their outcome.

## Libraries & Tool

- Python 
- Pandas, NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Tasks Completed

### Data Cleaning
- Loaded the dataset and explored its structure.
- Replaced zero values in Glucose, BloodPressure, and BMI with mean/median.
- Verified data types and checked for remaining missing values.

### Feature Engineering
- Created AgeGroup (e.g., Young, Middle-aged, Senior).
- Added BMICategory (Underweight, Normal, Overweight, Obese).

### Exploratory Data Analysis (EDA)
- Visualized distributions with histograms and boxplots.
- Compared diabetes outcomes across age groups and BMI categories.
- Used a correlation heatmap to identify feature relationships.

## 📊 Key Visualizations

### 1. Age Distribution

- Most individuals fall within the **30-50** age range.
- There is a noticeable drop-off in participants over 60 years old.
  
![Age Group](https://github.com/Kanu-Calista/Diabetes-EDA-project/blob/main/Project/Images/Diabetes_Outome_Across_Age_Groups.png?raw=true)

### 2. BMI Category Distribution

- The majority of individuals fall into the **Overweight** and **Obese** categories.
- Only a small fraction are **Underweight**, suggesting a greater concern for high BMI-related health risks.
- This trend may indicate potential lifestyle or dietary patterns in the population sampled

![BMI Category](https://github.com/Kanu-Calista/Diabetes-EDA-project/blob/main/Project/Images/Diabetes_distribution%20_by_BMI_category.png?raw=true)

### 3. Correlation Heatmap

- **BMI** and **Glucose** show strong positive correlation with diabetes outcome.
- **Age** has a moderate correlation with **Glucose** and **BMI**, Indicating increased risk with age.

![correalation matrix](https://github.com/Kanu-Calista/Diabetes-EDA-project/blob/main/Project/Images/Correlation_matrix.png?raw=true)

## Key Insights 

- **High Glucose = High Risk**  
  Individuals with glucose levels above 120 mg/dL were more likely to be diabetic.
- **Age Matters**  
  The likelihood of diabetes increases significantly in people aged 40 and above.
- **BMI Influences Outcome**  
  Overweight and obese individuals had a higher rate of diabetes compared to those with normal BMI.
- **Glucose is the Most Predictive Feature**  
  Among all features, glucose level had the strongest positive correlation with diabetes.

## Files

- `diabetes EDA project.ipynb` – main analysis notebook  
- `diabetes.csv` – dataset used  
- `Project/Images/` – folder with exported plots
