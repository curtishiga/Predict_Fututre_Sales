# Predict_Fututre_Sales

This repository contains all files relevant to the Kaggle competition "Predict Futrue Sales" which can be found at the following link:
[Competition Description](https://www.kaggle.com/c/competitive-data-science-predict-future-sales)

The objective of this playground competition is to predict the number of sales for a given item at a given shop for the succeeding month when they provide the sales of each shop and item for the previous 2 years.

This repository is laid out in the following structure:
- Data
  - This folder contains CSV files of the train and test set after feature engineering. This data is what's used to train and validate a machine learning algorithm.
- Data_Wrangling
  - Data_Wrangling.ipynb
    - This notebook is used for initial data exploration and to feature engineer the data to pass through machine learning algorithms.
    - Consider renaming file and folder to "Feature_Engineering"
- EDA
  - Exploratory_Data_Analysis.ipynb
    - Notebook exploring any patterns within the data
-Machine_Learning
  - Machine_Learning_Models.ipynb
    - Builds a random forest, XGBoost, and recurrent neural network to predict future sales.
- Predict Future Sales _ Kaggle_files
  - (This folder may not be necessary. Consider deleting)
- all
  - This folder contains the original data pulled from Kaggle. It provides the training and test sets, sample submission file, and dictionaries for the enumerated shop/items.
