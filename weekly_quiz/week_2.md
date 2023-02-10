# CASA0006 quiz week 2

Last update: 2023/01/18

Francesco Terenzi, Huanfa Chen

1. There are two types of problems in supervised learning. Which of the following statements are correct? **(2,3,4)**
   1. Clustering is one supervised-learning task
   2. Regression is one supervised-learning task
   3. Classification is one supervised-learning task
   4. Many models can be used for both supervised learning tasks

2. Which of the following statements are true about supervised learning? **(1,3,4)**
   1. In regression desired output consists of one or more continuous variables
   2. In classification, the training data consists of a set of input vectors x without any corresponding target values
   3. In classification, samples belong to two or more classes and we want to learn from already labelled data how to predict the class of unlabelled data.
   4. Training a model means to find the value of a set of parameters that best explain the given the data

3. While fitting data in a supervised-learning problem, overfitting is an important challenge. Which of the following are correct? **(2,3,4)**
   1. Overfitting causes a low accuracy on the training set
   2. Overfitting causes a low accuracy of the testing set
   3. Overfitting means that the model lacks generality (i.e. it won't predict accurately unseen data points)
   4. Comparing the model performance on the training and testing data will reveal the overfitting problem.

4. Some models have hyper-parameters. Which of the following statements are correct? **(2,3)**
   1. The values of the hyper-parameters are inferred from the data via the learning process (training)
   2. Cross-validation can be used to find the optimal values of the hyper-parameters
   3. Hyper-parameters a parameters whose values are used to control the learning process and cannot be inferred while fitting the machine to the training set

5. Which of the following statements are *NOT* true about randomness in supervised learning? **(3)**
   1. There is randomness in data splitting process (train vs test sets)
   2. There is randomness while learning the values of the model's parameters
   3. In scikit-learn, given some data and a model, we will always get different results while training a model
   4. To mitigate randomness, we should perform multiple runs and report average and standard deviation of performance
