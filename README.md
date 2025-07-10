# Risk Score Prediction In Bank Loan Application

## Repository Outline
```
- README(description).md | Overview of the project description.
- P1M2_Yonathan_Anggraiwan.ipynb | This notebook containing the codes and explanation of the data processing steps using Python.
- P1M2_Yonathan_Anggraiwan_inf.ipynb | This notebook containing the codes for model inference using Python and Pipelines.
- P1M2_Yonathan_Anggraiwan_dataset.csv | CSV dataset used for data analysis and making models.
- P1M2_Yonathan_Anggraiwan_conceptual.txt | A text file explaining conceptual problems, including the background and mechanism of bagging, the differences between how the Random Forest and Boosting algorithms work, and an explanation of Cross Validation.
```

## Problem Background
`I am a data analyst working in a department store. On this occasion, the store owner has asked me to analyze the annual sales data from their stores. I need to generate accurate analytical insights using statistics and create a visualization dashboard to answer key questions from the store executives.`

## Project Output
`The output of my project this time is best model to predict customer risk score (with regression, predict loan status approval (with classification), and present the result using huggingface website.`

## Data
`The dataset used in this project comes from Kaggle (https://www.kaggle.com/datasets/lorenzozoppelletto/financial-risk-for-loan-approval/data). It contains customer financial informations, with 20,000 rows and 36 columns. The dataset is considered clean, with no duplicate entries or missing values.
`

## Method
`In this moment, I compare five machine learning algorithms to predict an individual's RiskScore: KNN Regressor, Decision Tree Regressor, Random Forest Regressor, SVM Regressor, and XGBoost Regressor. The performance of these algorithms is evaluated based on their error score (MAE) and R² score, obtained through 5-fold Cross Validation for each algorithm. The best-performing algorithm will be further refined using hyperparameter tuning, after which the model will be saved and deployed on Hugging Face for inference and user access.`

## Stacks
`The programming language used in this project is Python, with VSCode as the development tool. The libraries used include pandas, scipy, statistics, numpy, matplotlib, seaborn, plotly.express, sklearn, and xgboost. Data visualization is also presented in EDA section and huggingface website.`

## Reference
`The supporting link for the results of this project analysis can be found in the following project dashboard link:
https://huggingface.co/spaces/rvpishere/Risk_Score_Prediction_In_Bank_Loan_Application`

---

**Additional Information:**
Contact Person:
- [E-mail](yonathan.anggraiwan.work@gmail.com)
