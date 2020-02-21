# Human_Disease_Prediction
Improve the bootstrap process and visualize the comparison of new and existing methods

# Introduction

*Scenario*

The data is from the Food and Agriculture Organization of the United Nations
that contains information on various outbreaks of animal diseases.
It has 17008 rows and 24 columns.In addition, the data shows when, where
and what of animal disease outbreaks from the last 2 years, including African
swine fever, Foot and mouth disease and bird-
u,numbers of cases, deaths or etc
are also included.
The outcome is whether human gets sick or not.

*Objectives*

The goal is to develop classiffication model to predict which outbreaks of animal diseases will lead to humans getting sick. Another goal is to compare the performance of two dierent types


*Tuning parameter selection*

In the Original data, Positive cases only takes 0.08331373. Thus, the odds of
positive versus negative cases was seemed as the previous model information
and added into the next model as tuning parameter.

*Gradient boosting*

Xgboost is a scalable end-to-end tree boosting system developed by Tianqi Xu.
It is based on a novel sparsity-aware algorithm for sparse data and weighted
quantile sketch for approximate tree learning.[1]

*Train models using Xgboost to predict the outcome*

The input data were revised to exclude redundant information and outcome.
The outcome were changed to a binary form. In addition, categorical variables
were transformed to sparse matrix. All of variables in training set were numeric
before training the model. The Xgboost system will select the most signicant
variables and the test error for the model picked by Xgboost.

*Compare the performance of two different types of splitting data*

Since the outcome is binary, performance of each model is measured by mis-classification rate. 









