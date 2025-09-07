WINE QUALITY PREDICTION
 Project Overview

This project develops a machine learning model to predict the quality of wines based on various physicochemical properties. Utilizing the UCI Wine Quality dataset, we apply data preprocessing, feature selection, and machine learning algorithms such as Random Forest, Support Vector Machine (SVM), and K-Nearest Neighbors (KNN) to classify wine quality on a scale from 0 to 10.

TECHNOLIGIES USED

Programming Language: Python

LIBRARIES:

pandas, numpy: Data manipulation and analysis

matplotlib, seaborn: Data visualization

scikit-learn: Machine learning algorithms and preprocessing

joblib: Model serialization

DEVELOPMENT :

Jupyter Notebook / Python Scripts

IDE: VS Code / PyCharm

PROJECT STRUCTURE
wine-quality-prediction/
1:-winequality-red.csv         # Raw dataset

2:-notebooks/
 wine_quality_analysis.ipynb # Exploratory Data Analysis
 
3:-models/
 train_models.py             # Model training and evaluation
  wine_quality_model.pkl      # Serialized model
  
4:- requirements.txt               # Project dependencies

5:-README.md                      # Project documentation

 DATASET

The dataset used in this project is the Red Wine Quality dataset from the UCI Machine Learning Repository. It contains 1,599 red wine samples with 11 physicochemical features:

fixed acidity

volatile acidity

citric acid

residual sugar

chlorides

free sulfur dioxide

total sulfur dioxide

density

pH

sulphates

alcohol

The target variable is quality, rated on a scale from 0 to 10.
