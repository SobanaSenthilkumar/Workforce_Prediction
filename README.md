
# Predicting Workforce Absenteeism Using Machine Learning

## Project Overview

This project focuses on predicting employee absenteeism using machine learning techniques. Absenteeism affects productivity, planning, and operational efficiency in organizations. By analyzing various employee-related features, this model helps identify patterns that influence absence duration, enabling better workforce management and informed decision-making.

## Dataset

The dataset contains 740 employee records with features such as:

* Age
* Workload
* Distance from home to workplace
* BMI and weight
* Education level
* Alcohol consumption
* Absence duration (target variable)

The target variable is categorized into three classes: Low, Medium, and High absenteeism.

## Methodology

1. **Data Cleaning**

   * Removed missing and duplicate values
   * Handled outliers using the Interquartile Range (IQR) method

2. **Exploratory Data Analysis (EDA)**

   * Studied distributions and correlations
   * Observed strong relationships (e.g., BMI and weight)

3. **Feature Processing**

   * Encoded categorical variables
   * Normalized numerical features

4. **Model Building**

   * Trained multiple models: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, AdaBoost, and XGBoost
   * Evaluated performance using accuracy and classification metrics

5. **Results**

   * XGBoost achieved the highest accuracy and stability in predicting absenteeism levels
   * Provided consistent and reliable predictions across test and validation sets

## Key Learning Outcomes

* Understanding real-world workforce behavior through data
* Applying preprocessing techniques such as outlier handling and feature encoding
* Comparing machine learning models and selecting the best-performing approach
* Interpreting model results for practical organizational use

## Conclusion

This project demonstrates how machine learning can be used to analyze workforce patterns and support better organizational planning. By predicting employee absenteeism, companies can allocate resources more efficiently and take informed actions to improve productivity.
