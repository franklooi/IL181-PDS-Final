# A (simple) Neural Network that beats Random Forest - Predicting Bikesharing Demand

Link to article: https://medium.com/@frank_66806/a-simple-neural-network-that-beats-random-forest-predicting-bikesharing-demand-8e83b117ea11

In this article, we will try to forecast the demand for bikes in a Bike Sharing program in D.C. The program has 2 years' worth of tabulated data and 17,379 rows, where each row represents an hour elapsed, some explanatory factors (e.g. weather, holiday) and how many bikes were rented within that hour.

The scope of this article is on model selection: we are trying to find the model that has the highest predictive power for this dataset. Our feature engineering will be kept to a minimum, pushing the models to find and extrapolate information from a fairly basic dataset.

## Overview

1. Data Exploration & Pre-Processing
2. Training a Single-layer Neural Network
3. Improving the Neural Network
4. Neural Network vs. Random Forest vs. XGBoost for Predicting Demand

## Results

![Predictions](https://cdn-images-1.medium.com/max/1600/1*HemRMDETMRV6dP8mZuS5eA.png)

![Model Results](https://cdn-images-1.medium.com/max/1600/1*iPkjd2iPIVxLzPjFeH6RjQ.png)

