# Product Recommendation Prediction Pipeline
## Problem Statement

Given a dataset of customer reviews, the goal is to predict whether a product will be recommended (1) or not (0). The dataset includes various features such as:

Numerical features: Age, Positive Feedback Count

Categorical features: Clothing ID, Division Name, Department Name, Class Name, Title

Text feature: Review Text

## Approach

The pipeline follows these key steps:

### Data Exploration:

1- Checking for missing values and duplicates

2- Visualizing age distribution and recommendation trends

3- Identifying the most positively reviewed product

### Feature Engineering:

Numerical features: Imputation and scaling using SimpleImputer and MinMaxScaler

Categorical features: Encoding using OrdinalEncoder and OneHotEncoder

### Text features:

Feature extraction using custom transformers

Lemmatization using spaCy

TF-IDF vectorization

## Model Training:

Building a pipeline using sklearn.pipeline

Training a RandomForestClassifier

## Model Evaluation:

Splitting the dataset into training and testing sets

Measuring model accuracy

## Fine-tuning hyperparameters using RandomizedSearchCV

## Libraries Used

#### pandas 

#### numpy

#### matplotlib & seaborn

#### scikit-learn: Machine learning pipeline, preprocessing, and modeling

#### spaCy

## Results

Initial accuracy of the model: 84.3%

After fine-tuning the model: 84.4%

## Conclusion

This project successfully demonstrates how to build an end-to-end machine learning pipeline incorporating numerical, categorical, and text data processing. The model achieves high accuracy in predicting customer recommendations, making it a valuable tool for businesses analyzing customer reviews.
