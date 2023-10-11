# Predictive Maintenance using Machine Learning Models

## Project Overview

This project focuses on predictive maintenance by utilizing machine learning models to predict equipment failures in advance. The dataset used contains operational parameters and sensor readings from machines. The goal is to predict whether a machine is likely to fail within a certain timeframe, allowing for proactive maintenance and minimizing downtime.

## Data Loading and Preprocessing

The dataset is loaded from a text file, and unnecessary columns (26 and 27) are removed. The columns are then renamed for better understanding of the data. Basic exploratory data analysis is performed to understand the data distribution.

## Exploratory Data Analysis (EDA)

1. **Dataset Shape and Columns**: The dataset consists of 20631 rows and 26 columns. The columns represent various operational parameters and sensor readings.
2. **Descriptive Statistics**: Statistical summary of the dataset provides insights into the central tendency and dispersion of the features.
3. **Missing Values**: There are no missing values in the dataset.
4. **Distribution of Cycles**: A histogram is plotted to visualize the distribution of cycle counts.
5. **Correlation Heatmap**: A heatmap is generated to understand the correlations between different features, which helps in feature selection.

## Feature Engineering

The target variable, 'failed', is created based on a threshold of remaining cycles. If the remaining cycles are less than or equal to 30, the machine is labeled as 'failed' (1), otherwise 'not failed' (0).

## Model Selection and Training

Four different machine learning models are trained and evaluated:

1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **Random Forest Classifier**
4. **Neural Network (Keras)**

The dataset is split into training and testing sets. Features are scaled using StandardScaler. Each model is trained and evaluated on accuracy and precision scores.

## Model Comparison

Model performance is compared based on accuracy and precision scores. Random Forest and Neural Network models show the highest accuracy and precision, making them suitable choices for predictive maintenance in this scenario.

## Conclusion and Future Steps

Predictive maintenance is crucial for industries to minimize downtime and increase operational efficiency. In this project, Random Forest and Neural Network models have demonstrated high accuracy and precision in predicting equipment failures. As a next step, the selected models can be deployed in real-time systems for continuous monitoring. Additionally, further tuning and optimization can be performed to enhance the models' performance. Continuous data collection and model retraining are essential to adapt to changing operational conditions and ensure the effectiveness of predictive maintenance strategies.

