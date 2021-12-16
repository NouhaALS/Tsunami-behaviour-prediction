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
<img width="333" alt="image" src="https://user-images.githubusercontent.com/86769038/146331744-50dc661e-12fb-4330-8ced-37be03c54934.png">

2. Top_corr_features

<img width="270" alt="image" src="https://user-images.githubusercontent.com/86769038/146331752-d2e1109d-39b0-4f74-9609-9c1cdc3e275f.png">

After feature engineering the remaining features are 13 out of 105

**Model**

1. linear regression

MAE =  0.74

MSE =  1.01

R^2 =  1.0

2. Sequential neural network

MAE =  0.11

MSE =  0.04

R^2 =  0.98


# tools

1. Numpy and Pandas for data processing
3. Matplotlib and Seaborn for visualization
4. Keras and Scikit-learn for modeling


# communication.
<img width="342" alt="image" src="https://user-images.githubusercontent.com/86769038/146331485-ffd08959-8a9c-427a-bddb-523009420c16.png">



