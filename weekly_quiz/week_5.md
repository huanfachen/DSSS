# CASA0006 quiz week 5

Last update: 2023/02/08

Xinglei Wang, Huanfa Chen

Tip: please choose one or more answers that you think are correct.

1. Which of the following statements about bias and variance (in machine learning context) are correct? **(134)**
   1. To measure bias or variance, multiple runs of models are necessary, which is
   similar to estimate the mean or variance of a variable.
   2. Variance can be measured by the difference between the expected (or average) prediction of our model and the correct value.
   3. Variance is manifested in the model's sensitivity to small fluctuations in the training data.
   4. The goal in many machine learning problems is to find a balance between these two sources of error and build a model that generalises well to new, unseen data.
2. Which of the following are true about model complexity? (**123**)
   1. Random forest models are more complex than linear regression model.
   2. The more splits a tree model has, the more complex it is.
   3. The more layers/neurons an ANN model has, the more complex it is.
   4. A complex model will always have higher variance than simpler ones.
3. Which of the following is generally helpful in reducing bias? (**145**)
   1. Increase model size/complexity
   2. Gather more data
   3. Regularization
   4. Feature engineering (e.g. constructing new x variables from existing ones)
   5. Using XGBoost to replace decision tree
4. Which of the following is helpful in reducing variance? (**123456**) (note: we haven't talked about regularisation/model pruning/early stopping in this module, so you can briefly introduce these concepts)
   1. Use simpler models
   2. Gather more data
   3. Regularisation
   4. Model pruning
   5. Cross validation
   6. Early stopping (used in training deep neural nets)

5. Which of the following process might have data leakage problem? (**12**)
   1. Normalize the data; do train-test split; train model on both training and testing set and evaluate on testing set.
   2. Normalize the data; do train-test split; train on training set; evaluate on testing set.
   3. Do train-test split; Normalize the data using only training set; train on training set; evaluate on testing set.