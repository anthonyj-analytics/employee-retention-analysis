# Employee Attrition Data Analysis and Prediction Using Logistic Regression

## Overview

The goal of this project was to understand the factors driving employee attrition at Salifort Motors, an imaginary French company specializing in alternative engines.

To achieve this, I used EDA (Exploratory Data Analytics) with Python, built a logistic regression model, and applied threshold optimization to improve predictive power.

This work enabled me to:
- Reveal strong attrition drivers such as such as workload imbalance, and limited performance-based rewards;
- Uncover 6 archetypes among workers, each describing a unique attrition pattern;
- Build a predictive model that reduces by 73% the risk of an employee leaving without early detection.

## Abilities
- [x] Understanding business context
- [x] Project proposal writing
- [x] Python: pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels, scipy
- [x] Exploratory Data Analysis (EDA): data cleaning, transformations, anomaly detection
- [x] Data visualization
- [x] Feature engineering
- [x] Statistical testing (Chi-squared)
- [x] Model design: selecting algorithms and exaluation strategies
- [x] Logistic regression modeling: assumptions, training, validation
- [x] Model evaluation: precision, recall, F-scores, ROC/AUC, accuracy
- [x] Threshold optimization for business-aligned decision-making
- [x] Executive-level reporting and synthesis

## Business understanding

Stakeholders: Senior leadership, HR team

This company is experiencing a high employee turnover, which leads to productivity loss, knowledge drain, and increased recruitment costs. Senior leadership and the HR team seek actionable insights to improve employee well-being and reduce attrition. Moreover, they also wish to identify employees at risk of leaving and to better understand the factors driving their decisions.

## Data understanding and limitations

- The dataset has near 15,000 entries, but around 20% of them were duplicates. 11,991 unique rows were analyzed, representing the number of employees.
- There were several variables including satisfaction level, evaluation score, workload, salary tier, promotion history and tenure.
- There were no demographic or qualitative data, limiting the explanatory power.
- Some feature categories had very low frequencies (like promotions and work accident).
- Attrition label is imbalanced (left employees consisting of the minority class with 16.6%). Modeling was made in a careful way to take that into account.
- Data provided is said to come from a HR survey. We don't know how the collect was done, how many people did not respond, or even if it was made carefully (20% duplicate rows indicate otherwise).
- There is no time indication as to when the satisfaction level and evaluation scores were taken respectively from one another, and we don't know how much time after these stats does the employees went away.
- Synthetic patterns in the data was found during EDA, meaning conclusions may not apply to real-world problems.
