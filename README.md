# Recursive_Feature_Elimination_CatBoost

## Introduction
A high number of features in small data exposes to the risk of overfitting. Overfitting is critical to model performance.
We release the Recursive Feature Elimation automation code that eliminates features sequentially by using CatBoost, which considers the correlation between features.

![rfe](https://user-images.githubusercontent.com/66405055/101464802-79631380-3982-11eb-8970-c07627918e34.PNG)


## Requirement

* [pandas](https://pypi.org/project/pandas/)
* [numpy](https://pypi.org/project/numpy/)
* [sklearn](https://pypi.org/project/scikit-learn/)
* [CatBoost](https://pypi.org/project/catboost/)


## How to Use

> 1. Load the data to select features selection.

> 2. Specify numeric features according to the guide in ipynb code.

> 3. Specifies the def RFE function.

> 4. For each round, determine the number of features to remove and the number of rounds.
