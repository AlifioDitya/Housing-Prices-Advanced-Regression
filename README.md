# Kaggle Competition: House Prices - Advanced Regression Techniques
This is a personal machine learning project to predict house sale prices using advanced regression techniques.
The current regression model has already been submitted on Kaggle with an RMSE score of 0.13435

## Dataset Description
_Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.
With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home._

**Directly Retrieved from [1]**

## Method
Prediction is made using a tree-based regression technique, specifically the XGBoost regressor, to predict house sale prices trained on `train.csv` and predicted with `test.csv`.
As mentioned before, the current regression model has an RMSE score of 0.13435 with a rank sitting at the top 90th percentile.

## Acknowledgments
The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset [1].
I would also like to give my appreciation to Krish Naik as the encoding and hyperparameter tuning steps are directly borrowed from the YouTube video referenced at [2].

## Reference
- [1] Anna Montoya, DataCanary. (2016). _House Prices - Advanced Regression Techniques_. Kaggle. https://kaggle.com/competitions/house-prices-advanced-regression-techniques
- [2] Krish Naik. (2019). _Kaggle Competition - House Prices: Advanced Regression Techniques Part1_ YouTube. https://www.youtube.com/watch?v=vtm35gVP8JU
