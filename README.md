## Dataset - "Online News Popularity Data Set"
This dataset summarizes a heterogeneous set of features about articles published by 
Mashable in a period of two years. The goal is to predict the popularity in 
social networks.

## Research Paper 1 - "A Proactive Intelligent Decision Support System for Predicting the Popularity of Online News"
### try.py (Original - paper1\data mining\try.pynb) - 
In this file an effort to replicate the paper "A Proactive Intelligent Decision 
Support System for Predicting the Popularity of Online News" has been made.

Python Version - Python 3.6

Libraries required - 
scikit-learn (sklearn) 
pandas
numpy

## Research Paper 2 - "Predicting the Popularity of Online News from Content Metadata"
### preprocessing.py (Original - preprocessing.pynb) - 
Data preprocessing is done in this file.
Generates two data files - 
Logarithmic tranformation on the continuous attributes - data.csv 
Normalization on the continuous attributes - datan.csv
Target attribute - target.csv

Python Version - Python 3.6
		
Libraries required -
pandas
matplotlib
numpy

### gbm.py (Original - gbm.pynb) -
Gradient Boosting Machine and Random Forest algorithms have been applied 
on the preprocessed file (data.csv and datan.csv). The resultant accuracies 
have been compared and in accordance with the research paper, GBM turned out
to be the better model. Parameter tuning has been performed to get the highest 
accuracy of 0.7151118.

Python Version - Python 3.6

Libraries required -
pandas
scikit-learn (sklearn)
numpy

### xgboostCheck.py (Original - xgboostCheck.pynb) -
xgboost algorithm has been used on the preprocessed file (data.csv). Parameter tuning 
has been done using GridSearchCV in sklearn and cv function in xgboost.

python Version - 3.6

Libraries required -
pandas
numpy
scikit-learn (sklearn)
xgboost
