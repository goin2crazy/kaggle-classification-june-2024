# Competition 

 This baselines wrote for [Classification with an Academic Success Dataset](https://www.kaggle.com/competitions/playground-series-s4e6). 
 I used many methobs for take the best score on test data:  
# 

 catboost | 0.835
 
 xgboost  | 0.828 
 
 lbgm     | 0.836 

# LGBM

getting the best scores on LGBM models the optuna optimization was add into new version of finding best params for models. With optuna & updated data preparation notebook model reached **0.838** score which is top 13% 

# Baseline 

- config
- data preparation (1 step: extracting new features from inputs, splitting X, y)
- data preparation (encoding categorical values)
- KFold Train & Validations splitting
- Run train model ( + adding models and accuracy into list to pick the most accurate model)
- Picking the most accurate 5 models
- Making submission with each model

