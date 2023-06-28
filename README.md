# Statistical Inference and Data Mining -- Mid-term Project

This repository contains our Mid-term project in the course on Statistical Inference and Data Mining. This project focuses on participating in the Kaggle competition "House Prices: Advanced Regression Techniques." The competition involves predicting house prices based on various features provided in the dataset.
### This project was done together with Chanel Michaeli.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Notebook Outline](#notebook-outline)
  - [Data Analysis](#data-analysis)
  - [Preprocessing](#preprocessing)
  - [Model Building](#model-building)
  - [Model Fitting and Evaluation](#model-fitting-and-evaluation)
  - [Submission](#submission)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In this project, we participate in the Kaggle competition "House Prices: Advanced Regression Techniques." Our goal is to build a regression model that accurately predicts house prices based on a given set of features. By leveraging statistical inference and data mining techniques, we aim to develop a robust model that achieves high performance on the competition's evaluation metrics.

## Dataset

The dataset for this project is provided by Kaggle and can be accessed through the competition link: [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview). It consists of a training set with labeled data and a test set without labels. The data contains various features related to residential properties, such as the number of rooms, the size of the property, location, etc. Detailed instructions, including the competition rules, data description, submission format, and model evaluation, can be found on the competition page.

## Notebook Outline

Our notebook follows a general outline to tackle the competition task effectively. The main sections of the notebook are as follows:

### Data Analysis

Perform exploratory data analysis (EDA) to gain insights into the provided dataset. This involves analyzing the distribution of variables, identifying potential outliers, visualizing relationships between features and the target variable (house prices), and exploring any patterns or trends in the data.

### Preprocessing

Preprocess the dataset to handle missing values, outliers, and other data quality issues. This step may include techniques such as imputation, outlier removal, feature scaling, and feature engineering to enhance the quality and usefulness of the data for modeling.

### Model Building

Build regression models using appropriate algorithms. For this project, we plan to use RidgeCV, a variant of ridge regression that automatically selects the optimal regularization parameter. Additionally, we will implement k-fold cross-validation to ensure robust model training and evaluation.

### Model Fitting and Evaluation

Fit the selected model to the training data and evaluate its performance. This involves assessing various regression evaluation metrics, such as mean squared error (MSE), root mean squared error (RMSE), and R-squared. We will use these metrics to compare the performance of different models and identify the most accurate one for predicting house prices.

### Submission

Create the submission file in the required format specified by the competition. This file will contain predictions for the house prices in the test set. Ensure that the submission adheres to the competition guidelines and submit it through the Kaggle platform.

## Usage

To use the code and reproduce the results of this project, follow these steps:

1. Clone the repository: `git clone https://github.com/NoamAtias/Statistical-Inference-and-Data-Mining-House-Prices-Advanced-Regression-Techniques.git`
2. Set up the Kaggle API and authenticate your account. Refer to the Kaggle documentation for instructions.
3. Download the
