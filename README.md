# EMPLOYEE ATTRITION PREDICTION ANALYSIS

  ![image](https://github.com/user-attachments/assets/39c4a242-c9b4-4512-853b-218c77825fc1)

## Overview

This project applies machine‑learning techniques to an HR analytics dataset to predict whether an employee is likely to leave the company and to identify the key factors that drive attrition. The resulting model can be operationalised by HR teams to flag high‑risk employees and deploy targeted retention strategies.

 ## Objectives

Predict attrition using historical HR data.

Rank feature importance to understand the strongest drivers of turnover.

Evaluate performance with accuracy, precision, recall, and F1‑score.

Deliver actionable outputs (e.g. high‑risk employee list) for proactive HR intervention.

#### Dataset source: IBM HR Analytics Employee Attrition & Performance (Kaggle)

 ## Methodology

Exploratory Data Analysis (EDA) – explored attrition patterns by department, role, satisfaction, compensation, and demographics.

Pre‑processing – removed low‑variance fields, encoded categorical variables, and standardised numeric features.

Model Training – baseline Logistic Regression followed by a tuned Random Forest (GridSearchCV).

Evaluation – assessed on a hold‑out 20 % test set.

Interpretation – ranked feature importances; exported probability scores for each employee.




