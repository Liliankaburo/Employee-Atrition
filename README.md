# HR ATTRITION PREDICTION ANALYSIS SYSTEM

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

## High‑Risk Employee Flagging

Employees with a predicted attrition probability ≥ 0.85 are flagged as high risk. The top 10 high‑risk cases in the test set all corresponded to actual leavers, validating the model’s effectiveness.

The full ranked list is saved to ***high_risk_employees.csv*** for HR review.

 ## Stakeholders

HR Business Partners – deploy insights to design retention actions.

People Analytics – maintain model and monitor drift.

Department Leaders – receive alerts for at‑risk staff in their teams.

## CONCLUSION

This project successfully demonstrated how machine learning can be applied to HR data to predict attrition, uncover risk factors, and enable proactive employee retention. The model can be integrated into HR workflows to monitor risk and inform data-driven decision-making.

## CONTACTS
Email ; lilian.k.mwabebe@gmail.com
linkedin ; https://www.linkedin.com/in/lilian-kaburo/
