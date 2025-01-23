# Customer Complaints Analysis and Dissatisfaction Prediction

This repository contains an analysis project aimed at gaining insights into customer complaints, understanding patterns of dissatisfaction, and building a predictive model to identify potential reasons for dissatisfaction before customer outreach.

## Project Overview

### Objective
1. Analyze historical data on customer complaints and profiles to extract insights and actionable recommendations.
2. Predict the reason for customer dissatisfaction using machine learning.

### Provided Data
The data is stored in a mock SQLite database and includes the following tables:
- **Complaints table**: Contains details about customer complaints.
- **Customer table**: Contains customer profiles and information.
- **Monthly reporting table**: Includes monthly updates on customer profiles.

## Tasks

### 1. Data Quality Checks and Preprocessing
- Perform data quality checks to identify:
  - Missing values
  - Duplicates
  - Invalid entries
- Preprocess the data:
  - Handle missing values and duplicates.
  - Standardize and normalize data where necessary.
  - Combine tables to create a consolidated dataset for analysis and modeling.

### 2. Exploratory Data Analysis (EDA)
- Perform EDA to understand:
  - Trends and patterns in complaints.
  - Correlations between customer attributes and dissatisfaction.
  - Common reasons for dissatisfaction.
- Visualize key insights using graphs and charts.

### 3. Machine Learning Model
- Train a machine learning model to predict the reason for dissatisfaction.
- Steps:
  1. Define target variable and features.
  2. Split data into training and testing sets.
  3. Train a suitable model 
  4. Perform hyperparameter tuning to optimize performance.

### 4. Model Evaluation
- Evaluate the model using metrics such as:
  - Accuracy
  - Precision, Recall, and F1 Score
  - ROC-AUC
- Summarize the results and compare performance across different models.

### 5. Findings and Recommendations
- Summarize insights from EDA and model results.
- Provide actionable recommendations based on:
  - Common dissatisfaction drivers.
  - Predicted reasons for dissatisfaction.
- Support findings with visualizations for clarity.


## Results and Insights
- **Key Findings**:
  - Common trends and drivers of dissatisfaction.
  - Predictive accuracy of the machine learning model.
- **Visualizations**:
  - Graphs highlighting patterns in complaints and customer profiles.
  - Model performance metrics.



