# FEATURE-ENGINEERING IN MACHINE LEARNING 

##FEATURE ENGINEERING IS THE MOST IMPORTANT STEP IN LIFECYCLE OF A DATA SCIENCE PROJECT.SO IT IS ESSENTIAL THAT WE HANDLE FEATURES IN A PROPER WAY AND APPROACH

Introduction
In my experience with supervised learning, improving the model performance from decent to human-like requires creative feature engineering. Jumping from simple algorithms to complex ones does not always boost performance if the feature engineering is not done right. The goal of supervised learning is to extract all the juice from the relevant features and to do that, we generally have to enrich and transform features in order to make it easier for the algorithm to see how the target variable depends on given data. One type of features that do not easily give away the information they contain are categorical features. They keep on hiding the information until we transform them smartly. In this particular post, I am focussing on one particular categorical encoding technique called target encoding which works really well most of the times, but it has a risk of target leakage if not done correctly. Target leakage means using some information from target to predict the target itself (you see the issue here?). This leakage consequently increases the risk of overfitting on the training data, especially when the data is small. Similar target leakage also exists in standard gradient boosting algorithms. Catboost has implemented a technique called ordering principle which solves the problem of target leakage in both cases. Based on this technique plus numerous other small improvements, Catboost outperforms other publicly available gradient boosting libraries on a set of popular publicly available datasets. The comparison experiments done by Catboost are summarized in this paper — CatBoost: unbiased boosting with categorical features.



This Repository Contain Feature Engineering Techniques

1.HOW TO HANDLE MISSING VALUES IN A NUMERICAL FEATURES.

2.HOW TO HANDLE MISSING VALUES IN A CATEGORICAL VARIABLES.

3.HOW TO HANDLE OUTLIERS IN A DATASET

4.HOW TO HANDLE CATEGORICAL VARIABLE:

*ONE-HOT ENCODING

*LABEL ENCODING

