# Marketing Campaign Offer Acceptance Prediction

This project uses interanl customer data to predict if a customer is likely to respond at or before 6 marketing campaign offers. The dataset can be found [here](https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign/data). It contains features that describe the product and amount purchased, customer demographics, method of purchase, and if the customer accepted a marketing campaign offer by the last marketing campaign.

this project consists of the following sections:
- Preprocessing
- Exploratory Data Analysis
- Exploration of Machine Learning Models
- Train and deploy best model

### Preprocessing
Steps include handling missing data and checking for duplicates as well as combining marketing offer acceptacne features into a single feature.

### Exploratory Data Anaysis
Explore the dataset and visualize numeric and categorical features.

### Exploration of Machine Learning Models
Data is scaled and the following models are explored:
 - Random Forest Classifier
 - Logistic Regression
 - K-Nearest Neighbors

## Train and deploy best model
The Random Forest Classifier performed best based on accuray and precision scores.
