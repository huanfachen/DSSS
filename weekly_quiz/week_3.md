# CASA0006 quiz week 3

Last update: 2023/01/26

Francesco Terenzi, Huanfa Chen

1. Classification and regression trees (CART) have hyper-parameters. Which of the following statements are correct? **(1,3)**
   1. CART's hyper-parameters represent a trade-off between performance and overfitting and are user-defined, though can be tuned by cross-validation.
   2. CART's hyper-parameters include the minimal depth of the tree and the maximal number of records on a node
   2. CART's hyper-parameters include the maximal depth of the tree and the minimal number of records on a node
   4. The values of the hyper-parameters are inferred from the data via the learning process (training)

2. Which of the following statements are correct about classification and regression trees? **(2,3,4)**
   1. One advantage of CART is smoothness: small perturbations in the input data do not dramatically change the response
   2. One advantage of CART is interpretability: it is easy to understand which features learnt generated the predictions
   3. One advantage of CART is flexibility: no assumptions of data distribution and no transformations needed
   4. One disadvantage of CART is overfitting: they do not easily generalise to new unseen data

3. CART are usually used as the base predictors of random forest (RF). Which of the following are correct? **(1,2,3)**
   1. RF constructs an ensemble of trees in parallel
   2. RF repeatedly samples datapoints and features during training producing different trees
   3. RF can be used for both classification and regression tasks

4. CART are usually used as the base predictors of gradient-boosted decision trees (GBDT). Which of the following are correct? **(2,3,4)**
   1. GBDT constructs an ensemble of trees in parallel
   2. During GBDT's fitting, a new CART predictor is trained using the residual from the last CART as the weight, considering the largest residuals
   3. GBDT has been used successfully in many data science competitions
   4. XGBoost is one efficient and scalable implementation of GBDT
   
5. CART are usually used in the context of random forest (RF) and gradient-boosted decision trees (GBDT). Which of the following are correct? **(1,2,3,4)**
   1. RF and GBDT are ensemble learning methods based on CART which improve CART's lack of robustness (overfitting + smoothness)
   2. RF and GBDT models non-linear relationships between features
   3. Both RF and GBDT lack interpretability
   4. By averaging multiple trees, RF's and GBDT's predictions are more robust compared to those of individual CARTs
