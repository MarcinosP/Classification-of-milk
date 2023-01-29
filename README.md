# Classification-of-milk

The notebook shows a project, in which I created a data classification model.

Link to data used in notebook:
[kaggle](https://www.kaggle.com/datasets/cpluzshrijayan/milkquality)

issues implemented in the project:
- Data preparation
  - filling missing data
    - by mode
    - with regression
    - by MICE method
  - scaling data
    - standarization
    - min-max (all features are scaled to be in range for example 0-1)
- classification
  - DecisionTreeClassifier
  - SVCClassifier
  - SGDClassifier
  - RandomForestClassifier
- self implemented cross validation
- team learning
  - voting classifier
  - stacking classifier
  - bagging classifier
  - xgboost
- optimalization
  - removing features by correlation
  - unvariate testing
  - extra tree calssifier
  - rfe
- hyperparameter optimization
  - grid search
  - optuna
