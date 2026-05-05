# Camptothecin Drug Resistance Prediction

## Overview
End-to-end supervised machine learning pipeline analyzing Camptothecin 
drug resistance across 967 cancer cell lines using genomic and 
pharmacological data from the GDSC database.

## Key Results
- **95.2% test recall** on final tuned Random Forest model
- Optimized for false negative minimization given clinical cost of missed resistance
- 87 features engineered from genomic and pharmacological profiles

## Methods
- Exploratory Data Analysis
- Inferential Statistics
- Binary classification via median-split RESISTANT variable
- GridSearchCV hyperparameter tuning
- Model selection: Tuned Random Forest (selected over ensemble classifiers)

## Tools & Libraries
Python | pandas | scikit-learn | matplotlib | seaborn | Jupyter
