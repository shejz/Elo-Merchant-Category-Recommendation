# [Elo Merchant Category Recommendation](https://www.kaggle.com/c/elo-merchant-category-recommendation)
How can machine learning be used to best predict customer loyalty using Elo's dataset from the [Merchant Category Recommendation Kaggle Competition](https://www.kaggle.com/c/elo-merchant-category-recommendation)?


## **Competition Objective**
- Predict any given customer's loyalty score based on the customer's past purchasing behaviour.
- We will be given a credit card data set to train their prediction model, then submit their preditions for credit cards in a test set.

## **Dataset Overview**

**Dataset Description**:
- The datasets are largely anonymized, and the meaning of the features are not elaborated. External data are allowed

**File descriptions**
- train.csv - the training set
- test.csv - the test set
- historical_transactions.csv - up to 3 months' worth of historical transactions for each card_id
- merchants.csv - additional information about all merchants / merchant_ids in the dataset.
- new_merchant_transactions.csv - two months' worth of data for each card_id containing ALL purchases that card_id made at merchant_ids that were not visited in the historical data.
- sample_submission.csv - a sample submission file in the correct format - contains all card_ids you are expected to predict for.

**Data fields**
Data field descriptions are provided in Data Dictionary.xlsx.

## **Metric**
The overall performance metric is the root-mean-squared error (RMSE). Lower RMSE is more desirable.


## **Submissions & Leaderboard Scores**

|Models            |Public score|Private score|Final rank| 
|------------------|------------|-------------|----------|
|LightGBM          |3.69199     |3.61748      |    -      |
|LGBM CV Bagging   |3.69148     |3.61647      |    -      |
|Without outliers  |3.69254     |3.61947      |    -      |
|Blending I        |3.68771     |3.61385      |Top **12%** 480/4127|
|Blending II       |3.68747     |3.61337      | Bronze medal 🥉          |



