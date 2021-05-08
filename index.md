# Welcome to my portfolio website

# Project

# 1) Mechanism of Action Prediction

This challenge was hosted on Kaggle by The Connectivity Map, the Laboratory for Innovation Science at Harvard (LISH), and the NIH Common Funds Library of Integrated Network-Based Cellular Signatures (LINCS).

The goal of this challenge was to predict the Mechanism of Action of drugs based sets of features. These features were based on the effect of the drug on the cellular viability and gene expression. The data was collect after treating cells with these drug at two different doses for three distinct treatment durations. The information about the identity of the drug, the recorded features and doses of the drug were anonymized.

The major challenges I encountered in this projects are:
1) How to predict **206** labels- a multi-label classification problem
2) How to stratify a multi-label datasets for a balanced train-test-split
3) How to minimize the **logloss** of the multiple models

I tried logistic regression, Random forest, xgboost, Dense neural network and eventually found an ensemble of xgboost and DNN worked best.

The [notebook](https://github.com/pdubey2018/MoA_kaggle/blob/main/notebooks/predicting-mechanism-of-action-of-drugs.ipynb) describes EDA and model building, various hyper-parameter tuning experimentation. 


