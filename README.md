# TPS6-Kaggle
This repository contains my Jupyter notebooks for the Kaggle Competition: Tabular Playground Series June 2021

<b>About the competition:</b>

The dataset is used for this competition is synthetic, but based on a real dataset and generated using a CTGAN. The original dataset deals with predicting the category on an eCommerce product given various attributes about the listing. Although the features are anonymized, they have properties relating to real-world features.

Type: Multiclass Classification (9 classes)

Evaluation Metric: Multiclass Log Loss

<b>My repository contains the following notebooks:</b>
- tps6-eda-comparison-to-tps5.ipynb
    - EDA (Exploratory Data Analyses)
    - comparison to previous competition which also was Multiclass Classification with Log Loss metric
- tps6-xgboost-a-stepwise-approach-to-gridsearch.ipynb
    - XGBoost
    - step wise hyperparameter tuning using GridSearch 
- tps6-boost-your-score-with-knn-features.ipynb
    - feature generation using the Gokinjo package (KNN algorithm)
- tps6-kmeans-features.ipynb
    - feature generation using a kmeans algorithm
- tps6-postprocessing.ipynb
    - handling feature duplicates in train and test set 


