# Predicting the Tsunami Behaviour from Historical Data

Nouha o. Alsaleh
# Abstract

The goal of this project was to build a regression model of the historical tsunami data to get insights and understand the tsunami behaviour from it features aiming to visualize the distribution of tsunami in each ocean using explanatory data analysis (EDA). This project will compare the results of the linear regression and neural network to find the best model for the given data, moreover, the prediction goal here is the horizontal runup which means the maximum height of the tsunami wave relatively to the normal shoreline position, taking feature selection to further filter out the unrelated features.

# Design

This project used historical tsunmai events data that start from 2100 BC to the present, but to make the prediction more relavant to this century this project execluded anything before AD. The goal is to predict tsunami runups to estimate damage and how intense future tsunami is behaving which helps to take precautions and preparation in case of tsunami, espically for at risk countries such as japan, oman, ...etc.


# Data 

The dataset is "Historical Tsunami Event" from [data world](https://data.world/dhs/), it contains  26,824 rows (entry) and 105 columns (feature). This dataset provides information on over 2,400 tsunamis from 2100 BC to the present in the Atlantic, Indian, and Pacific Oceans, and the Mediterranean and Caribbean Seas. 

# Algorithms

**feature engineering**

1. ExtraTreesClassifier
2. Top_corr_features

**Model**

linear regression, Sequential neural network


# tools
1. Numpy and Pandas for data processing
2. Matplotlib and Seaborn for visualization
3. Keras and Scikit-learn for modeling


# communication.
