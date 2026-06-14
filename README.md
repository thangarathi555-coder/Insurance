# Medical Insurance Cost Analysis and Prediction System

## Introduction

Health insurance plays an important role in managing medical expenses and providing financial security to individuals. Insurance companies collect large amounts of customer information such as age, gender, BMI, number of children, smoking habits, region, and insurance charges. Analyzing this data manually is difficult and time-consuming. Data Analytics and Machine Learning techniques can help identify patterns, predict insurance costs, and support better decision-making.

This project uses Exploratory Data Analysis (EDA), Linear Regression, Multiple Linear Regression, Logistic Regression, and Dashboard Visualization to analyze customer data and predict insurance charges accurately.

## Problem Statement

Insurance companies need to estimate medical insurance premiums based on customer information. Incorrect premium estimation can lead to financial losses, unfair pricing, and poor risk assessment. Large volumes of customer data make manual analysis difficult and inefficient.

Therefore, an automated system is required to analyze customer information, identify factors affecting insurance costs, classify customer risk levels, and predict future insurance charges using Machine Learning techniques.

## Objectives

* Import and analyze the Medical Insurance dataset.
* Clean and preprocess the data.
* Perform Exploratory Data Analysis (EDA).
* Identify factors influencing insurance charges.
* Compare insurance costs based on age, BMI, gender, region, and smoking habits.
* Build Linear Regression models for insurance cost prediction.
* Build Multiple Linear Regression models using multiple factors.
* Develop a Logistic Regression model to classify customers into High Cost and Low Cost categories.
* Create interactive visualizations and dashboards.
* Generate insights for better premium estimation and risk assessment.

## Tools and Technologies Used

**Programming Language:** Python

**Libraries:**

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Plotly

**Dataset Source:** Kaggle Medical Cost Personal Dataset

## Methodology

### Step 1: Data Collection

The insurance dataset is collected from Kaggle and loaded into Python for analysis.

### Step 2: Data Loading

The dataset is imported using Pandas DataFrame.

### Step 3: Data Cleaning

* Check missing values
* Remove duplicate records
* Encode categorical variables
* Verify data types

### Step 4: Exploratory Data Analysis (EDA)

Statistical analysis is performed to understand:

* Average age
* Average BMI
* Average insurance charges
* Average number of children

### Step 5: Data Visualization

Various charts are created to analyze insurance patterns:

| Visualization | Purpose                                    |
| ------------- | ------------------------------------------ |
| Histogram     | Distribution of age, BMI, and charges      |
| Scatter Plot  | Relationship between age, BMI, and charges |
| Bar Chart     | Region-wise insurance charges              |
| Box Plot      | Smoker vs Non-Smoker comparison            |
| Heatmap       | Correlation analysis                       |
| Pie Chart     | Gender and smoker distribution             |

### Step 6: Machine Learning Models

#### Linear Regression

Predict insurance charges using age as the independent variable.

#### Multiple Linear Regression

Predict insurance charges using:

* Age
* BMI
* Children
* Smoker Status

#### Logistic Regression

Classify customers into:

* Low Cost Customer (0)
* High Cost Customer (1)

based on the median insurance charge value.

### Step 7: Model Evaluation

Regression Models:

* R² Score
* MAE
* MSE
* RMSE

Classification Model:

* Accuracy
* Confusion Matrix
* Precision
* Recall
* F1-Score

### Step 8: Dashboard Creation

Interactive dashboards are created using Plotly to visualize:

* Insurance Charge Distribution
* Age vs Charges
* BMI vs Charges
* Smoker vs Non-Smoker Comparison
* Region-wise Charges
* Correlation Heatmap
* Customer Risk Categories

## Expected Output

The project provides:

* Insurance cost predictions
* High-risk customer identification
* Customer segmentation
* Interactive visualizations
* Machine Learning model performance metrics

## Applications

* Health Insurance Companies
* Risk Assessment Systems
* Premium Estimation
* Healthcare Analytics
* Customer Segmentation
* Business Decision Support Systems

## Conclusion

This project demonstrates how Data Analytics and Machine Learning techniques can be applied to insurance data for cost prediction and risk assessment. Through EDA, Regression Models, Logistic Regression, and Dashboard Visualization, meaningful insights can be generated to support insurance companies in premium estimation and policy planning. The system helps improve decision-making, reduce risks, and provide fair insurance pricing for customers.
