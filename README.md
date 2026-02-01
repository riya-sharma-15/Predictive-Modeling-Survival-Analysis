# Titanic Survival Analysis — End-to-End Data Analytics Project

 ## Project Overview

This project presents an end-to-end data analytics workflow using the Titanic passenger dataset. The objective is to analyze the factors influencing passenger survival by combining data exploration, statistical analysis, predictive modeling, and visualization techniques across multiple tools. The project demonstrates how raw data can be transformed into meaningful insights using Python, Excel, and Tableau, reflecting a real-world analytical pipeline.

## Objectives

- Perform Exploratory Data Analysis (EDA) to understand data patterns and relationships
- Identify key factors affecting passenger survival
- Build a baseline predictive model using Logistic Regression
- Analyze and summarize insights using Excel
- Create interactive visualizations using Tableau
- Present findings in a structured, portfolio-ready format

## Dataset

- Source: Kaggle Titanic Dataset
- Description: Passenger information including demographics, ticket details, and survival status
- Target Variable: Survived
- Key Features: Age, Sex, Pclass, Fare, Embarked, SibSp, Parch

## Tools & Technologies

- Data Cleaning & EDA: Python(Pandas, NumPy, Matplotlib, Seaborn)
- Modeling: Scikit-learn(Logistic Regression)
- Data Analysis:	Microsoft Excel
- Visualization: Tableau
- Version Control: Git & GitHub

## Project Workflow

### 1) Data Exploration & Preprocessing (Python)

- Loaded and inspected the dataset
- Analyzed data types and summary statistics
- Handled missing values (Age, Embarked)
- Removed features with excessive missing values (Cabin)
- Performed univariate and multivariate analysis
- Conducted correlation analysis
- Engineered additional features such as family size and passenger titles

### 2) Predictive Modeling (Python)

- Built a Logistic Regression model to establish a baseline classification framework
- Prepared features using encoding and scaling techniques
- Split data into training and testing sets
- Evaluated model performance using accuracy, confusion matrix, and AUC score
- Analyzed feature impact on survival prediction using model coefficients

Note: The model is intended as a baseline learning model. More advanced classification techniques can be explored in future work.

### 3) Data Analysis (Excel)

- Imported cleaned dataset from Python
- Created pivot tables and summary reports
- Analyzed survival trends by class, gender, age group, and fare range
- Performed basic statistical analysis
- Developed structured analytical views for reporting

### 4) Data Visualization (Tableau)

- Built interactive dashboards and charts
- Visualized survival patterns across demographics and classes
- Created filters and drill-down views for deeper exploration
- Designed user-friendly visual storytelling dashboards

## Key Results & Insights

- Female passengers had significantly higher survival rates than males
- First-class passengers were more likely to survive than third-class passengers
- Higher fare values were positively correlated with survival probability
- Passengers traveling with small families showed better survival outcomes
- The Logistic Regression model achieved approximately 83% accuracy in predicting survival
