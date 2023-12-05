# Binary Prediction of Smoker Status using Bio-Signals
## Aim
To predict a patient's smoking status given information about various other health indicators.
## Link to the competition
[\<click!\>](https://www.kaggle.com/competitions/playground-series-s3e24)
## Score
AUC = 0.873
## Approach
    1. brief EDA
    2. apply feature engineering (adding features, dropping features, clustering with the different groups of features)
    3. evaluate the basic models
    4. create the ensembles of best-performing basic models (2-4 basic models in one ensemble)
    5. evaluate such ensembles and find out the one that performs best
## Used techniques
### Libraries
    1. pandas
    2. numpy
    3. itertools
    4. matplotlib
    5. seaborn
    6. sklearn
    7. xgboost
    8. lightgbm
    9. catboost
### Preprocessing
    1. EDA
    2. Outliers dropping
    3. Adding new features
    4. Dropping redundant features
    5. Clustering by different features groups
    6. Normalization
### Learning
    1. Logistic Regression
    6. HistGBM Classifier
    7. XGBM Classifier
    8. AdaBoost Classifier
    9. LightGBM Classifier
    10. CatBoost Classifier
    12. Ensembles
    13. Cross-Validation
    14. Hyperparameter optimization
