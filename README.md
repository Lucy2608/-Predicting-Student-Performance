# Predicting Student Performance

# Project Overview
This project aims to predict the final grades (G3) of students based on a variety of influencing factors such as attendance, study hours, socioeconomic background, and other attributes. The goal is to build a regression model that accurately forecasts student outcomes to help identify at-risk students early and support targeted interventions.

# Dataset
Source: Kaggle's Student Performance Dataset (student-mat.csv)

# Content

Data from Portuguese schools including 395 records with 33 input features capturing demographics, academic history, social activities, and family background.

# Target variable:

Final grade in mathematics (G3), scored 0 to 20.

# Problem Importance

1. Enables educators to better allocate resources and offer support.

2. Helps parents and policymakers understand the impact of various factors on student success.

3. Builds practical skills for predictive modeling in education.

# Methodology

1. Data preprocessing and feature engineering to create a clean dataset suitable for modeling.

2. Correlation analysis identified key predictors like prior grades (G1, G2), parental education, and failures that influence final grades.

3. Multicollinearity diagnosed with Variance Inflation Factor (VIF), leading to selecting features with minimal redundancy.

4. Model building involved training a Random Forest Regressor to capture both linear and non-linear relationships.

5. Model evaluation used RMSE, MAE, and R² metrics—achieving an RMSE of 2.355 and explaining 73% of grade variance.

6. Feature importance visualization highlighted prior academic performance as the dominant factor influencing predictions, with social and family factors playing smaller roles.

# Results Summary

1. The Random Forest model reliably predicts final grades with reasonable accuracy.

2. Prior academic scores (G1_G2_avg) contribute 88.6% importance to the model, confirming past performance as the primary predictor.

3. Lifestyle factors such as going out, failures, and travel time also influence, but to a lesser extent.

4. The model can support early identification of students at risk, aiding proactive educational interventions.

# Future Work

1. Experiment with additional models like Gradient Boosting or Neural Networks.

2. Incorporate more nuanced social or psychological factors.

3. Build a deployment pipeline for real-time predictions in schools.

