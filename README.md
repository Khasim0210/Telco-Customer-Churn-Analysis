# Telco Customer Churn Analysis

This project presents an end-to-end data science analysis of customer churn in the telecom industry. 
The goal is to identify key factors driving churn and provide data-driven recommendations to improve customer retention.

## Business Objective

Customer churn is a major challenge for telecom companies, as acquiring new customers is more expensive than retaining existing ones.  
The primary objective of this project is to analyze customer behavior, identify the key drivers of churn, and build a predictive model to help the business proactively retain high-risk customers.


## Dataset Overview

The dataset used in this project contains customer-level information from a telecom company, including demographic details, services subscribed, contract information, billing data, and churn status.

- Total records: 7,043 customers  
- Total features after cleaning: 20  
- Target variable: `Churn` (Yes = customer left, No = customer retained)



## Project Workflow

The project follows a structured end-to-end data science workflow:

1. Data Cleaning and Preprocessing  
   - Handled missing and incorrect values  
   - Converted data types and removed irrelevant features  

2. Exploratory Data Analysis (EDA)  
   - Analyzed churn distribution  
   - Identified key patterns and relationships affecting churn  

3. Feature Engineering and Scaling  
   - Encoded categorical variables  
   - Created derived features to capture customer behavior  
   - Scaled numerical features for model training  

4. Modeling and Evaluation  
   - Built baseline and improved classification models  
   - Evaluated models using accuracy, recall, and ROC-AUC  

5. Business Insights and Recommendations  
   - Interpreted model results  
   - Provided actionable strategies to reduce customer churn
