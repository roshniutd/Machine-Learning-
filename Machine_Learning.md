  For supervised Machine Learning in Avacado dataset
    --> Using Grid Search we found the best scaling parameter and applied all the learning models to see which one performs best.
    --> Finally, found that the best regressor for this dataset was a SVR model with kernel rbf

  For supervised Machine Learning in Chicago Food inspections dataset
    --> Using Grid Search we found the best scaling parameter and applied all the learning models to see which one performs best.
    --> Finally, found that the best model was the K nearest classifier

  For both the Classification dataset and Regression dataset the following Optimization trechniques are applied and the difference in performance is observed
    --> Voting classifiers - one with hard voting and one with soft voting
    --> Bagging and Pasting
    --> Adaboost boosting
    --> Gradient boosting
    --> PCA on data and then apply all the models on data you get from PCA. Compare your results with results. 
    --> Deep learning models 
