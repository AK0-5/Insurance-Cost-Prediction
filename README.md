# Insurance-Cost-Prediction
This project predicts how much medical insurance cost different types of people are likely to require based on their demographic and health-related attributes.
It helps identify which individuals are expected to incur higher or lower insurance costs using regression models.

# Insurance Cost Prediction using Regression
##  Problem Statement
Medical insurance companies need to estimate insurance charges accurately based on individual characteristics such as age, BMI, smoking status, and family size.
This project aims to build regression models that can estimate insurance costs and analyze the factors influencing them.

## What This Project Does

- Predicts insurance charges (cost amount) for individuals
- Identifies which type of people require higher insurance cost
- Analyzes the impact of factors like:
Age
BMI
Smoking status
Number of children
Gender
Region

- Compares Linear, Ridge, and Lasso Regression
- Uses residual analysis to evaluate model behavior

## Dataset
Medical Insurance Dataset containing demographic and health-related information.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Workflow
1. Data loading and preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature encoding and scaling  
4. Train-test split  
5. Linear Regression  
6. Ridge and Lasso Regression  
7. Residual analysis and visualization  
8. Model comparison and evaluation  

## Key Insights
- Smokers require significantly higher insurance costs
- Age and BMI strongly influence insurance charges
- Gender and region have minimal impact
- Regularization improves model stability
- Residual analysis reveals model limitations at high-cost ranges

## Models Used
- Linear Regression
- Ridge Regression (L2 regularization)
- Lasso Regression (L1 regularization & feature selection)

## Files
- `Insurance_Cost_Prediction.ipynb` – Complete project code  
- `insurance.csv` – Dataset  

## Conclusion
This project demonstrates how regression models can be used to predict insurance costs and understand which types of individuals are more expensive to insure, making it useful for pricing strategies and risk analysis.
