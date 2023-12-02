# Predicting-Sleep-Metrics
### Individual Project
### Peter Nguyen
### December 2, 2023

## Introduction
The objective of this project is to implement a multiple linear regression model that effectively predicts how many hours of sleep a person is getting and the quality of their sleep. This prediction will be based on a set of specific factors, allowing us to gauge the influence of these elements on sleep patterns and provide insights into the persons sleep metrics.

Sleep is a vital aspect of overall health and well-being, influencing various physiological and psychological functions. Understanding the factors affecting sleep patterns and their implications on health is crucial. The Sleep Health and Lifestyle Dataset aims to provide insights between sleep metrics, and lifestyle factors among individuals.

While the dataset is synthetic, the analysis aims to mirror real-world scenarios, offering illustrative findings that may be extracted and interventions in the field of sleep health.

In pursuit of implementing a prediction model using multiple linear regression, I utilized w3schools as a resource to gain an understanding of the process.

By delving into a wide range of variables, we seek to unravel the intricate dynamics that contribute to variations in sleep patterns.
### 1.1 Objectives/Research Questions
1. How well does the multiple linear regression model predict how many hours of sleep a person gets based on lifestyle and health factors?

2. Can the model be extended to predict Sleep Quality?

3. How do Exercise, Stress Level, and Age influence Sleep Duration and Sleep Quality? What are their relationships?

## 2. Data Selection
The Sleep Health and Lifestyle Dataset, presented in this report, is a synthetic dataset, acknowledging its origin as a product of artificial generation rather than real-world observations. 

The dataset is derived from Kaggle[1], comprising of 400 rows and columns, the dataset encapsulates a diverse array of variables, including sleep metrics, and different lifestyle factors. The factors the data provided includes sleep duration, sleep quality, physical activity levels, stress, and age. 

The authors states that the dataset also utilizes methods like filling in missing values and crafting new variables to mimic real-life situations. Imputation was also used to handle missing data and enhance the dataset’s completeness, while feature engineering involved crafting additional variables to make the dataset more comprehensive. 

The model training is implemented in Jupyter and is available here.

Data Preview:

I have intentionally chosen a subset of columns from the dataset, specifically focusing on those that exclusively contain numerical values.


