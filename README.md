## Mercedes Benz Greener Manufacturing 

This repository contains the work done on the [Mercedes Benz Greener Manufacturing Kaggle competition](https://www.kaggle.com/c/mercedes-benz-greener-manufacturing) 

**Objective of the competition**: Cut the time a Mercedes-Benz spends on the test bench

**Evaluation criteria**: R^2

**Performance**: 

| Submission identifier   |      Public leaderboard score (R^2)      |  Private leaderboard score (R^2) | Delta to Rank #1 | 
|----------|:-------------:|:------:| :------:|
| submission-1498065002 |  0.55766 | 0.55269 | 0.00282|
| submission-1498060103 |    0.56843   |   0.55162 | 0.00389|
| submission-1498405256 | 0.55030 |    0.55298 | 0.00253|

**Techniques learnt in this competition**:
* Outlier detection and handling.
* Out of fold train and prediction, due to small train set.
* Preventing overfitting.
* Model ensembling.


**Notes on this competition**:
* Compleatly obfuscated dataset containing 8 categorical features and 370 binary featues. This made feature engineering non-trival.  
* Test data set and train data set are the same size but only conained 4209 rows each
* ~12% of the train data had exact same features but different target variables, implying duplicate values. 
* Another bottleneck to accuracy was outliers which heavily skewed R^2.  
