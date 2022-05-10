# Monsoon CreditTech Assignment
Prediction of loan outcome using lending company dataset, historical information about loan disbusement, like loans taken by a borrower, loans applied by a borrower, etc.


## Dataset
Download link can be found [here](https://drive.google.com/file/d/152PXuKYuKXvzAg1DT2s5ZCcStC5iezzi/view?usp=sharing).

## Model Metrics

Used multiple machine learning models


| Algorithm | Accuracy     | ROC-AUC Score                 |
| :-------- | :------- | :------------------------- |
| Logistic Regression | 51% | 53.08% |
| Random Forest | 86% | 44% |
| XGBoost | 90% | 94.8% |


We can see even though best `ROC-AUC Score` is achieved by XGBoost

## Installation
1. Clone this repository in your local system
2. Run: ``` pip install -r requirements.txt ```

## Run
1. Make sure you have jupyter notebook installed
2. Go to the project directory and run ``` jupyter notebook ```
