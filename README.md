# Kaggle contest for the students of the Data Scientist course at School 21 Sber / Tomsk State University. 2022

Task: predict rent price at airbnb in London.

Metric: mean absolute error.

Files:
1. EDA.ipynb - data analysis
2. pca.ipynb - principal component analysis. 2 main components explain 97% of variance, but using only these two did not improve results.
3. regression.ipynb - gradient boosting with hyperparameter selection by cross-validation. Sklearn pipeline to prepare data and predict
4. regression_next_incomplete.ipynb - work in progress, incomplete.