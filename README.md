# Online News Popularity

Implementation of two research papers to find the best algorithm that predicts the popularity of a news article. Done for the course of "Data Mining"
## Dataset - "Online News Popularity Data Set"
This dataset summarizes a heterogeneous set of features about articles published by 
Mashable in a period of two years. The goal is to predict the popularity in 
social networks.

## Research Paper 1 - "A Proactive Intelligent Decision Support System for Predicting the Popularity of Online News"
### try.ipynb 
In this file an effort to replicate the paper "A Proactive Intelligent Decision 
Support System for Predicting the Popularity of Online News" has been made.

## Research Paper 2 - "Predicting the Popularity of Online News from Content Metadata"
### preprocessing.ipynb 
Data preprocessing is done in this file.

Generates two data files - 
- Logarithmic tranformation on the continuous attributes - data.csv 
- Normalization on the continuous attributes - datan.csv
- Target attribute - target.csv

### gbm.ipynb
Gradient Boosting Machine and Random Forest algorithms have been applied 
on the preprocessed file (data.csv and datan.csv). The resultant accuracies 
have been compared and in accordance with the research paper, GBM turned out
to be the better model. Parameter tuning has been performed to get the highest 
accuracy of 0.7151118.

### xgboostCheck.ipynb
xgboost algorithm has been used on the preprocessed file (data.csv). Parameter tuning 
has been done using GridSearchCV in sklearn and cv function in xgboost.

## Software Requirements
- python Version - 3.6
- Libraries required -
    - pandas
    - numpy
    - scikit-learn
    - xgboost
    - matplotlib

