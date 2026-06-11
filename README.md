### Linear Regression Analysis with Python
### Overview

This lab introduces the fundamentals of predictive analytics through the implementation of a Linear Regression model using Python and Scikit-learn.

Using the California Housing dataset, the project explores the complete machine learning workflow, including:

### Data loading and preparation
Train-test splitting
Linear Regression model training
Model evaluation using Mean Squared Error (MSE)
Performance analysis using R² Score

### Dataset
The project uses the California Housing dataset available through Scikit-learn.

### Features
The dataset contains housing-related attributes including:
Median Income
House Age
Average Rooms
Average Bedrooms
Population
Average Occupancy
Latitude
Longitude
Target Variable
Median House Value

## The objective is to predict housing prices based on the provided features.
## Project Tasks
1. Data Preparation
Imported required Python libraries
Loaded the California Housing dataset
Created feature and target variables

2. Train-Test Split
The dataset was divided into:
80% Training Data
20% Testing Data
This allows the model to learn patterns from the training set while being evaluated on unseen data.

3. Linear Regression Model
A Linear Regression model was implemented using Scikit-learn.
The model learns the relationship between housing characteristics and median house values by fitting a linear equation to the training data.

4. Model Evaluation – Mean Squared Error (MSE)
## Results:
Dataset	MSE
Training	0.518
Testing	0.556
The testing MSE is only slightly higher than the training MSE, indicating good generalization and minimal overfitting.

5. Model Evaluation – R² Score
## Results:
Dataset	R² Score
Training	0.613
Testing	0.576

The model explains approximately:
61.3% of the variance in housing prices on training data
57.6% of the variance in housing prices on testing data

## Key Findings
The model demonstrates moderate predictive performance.
Training and testing metrics are relatively close, suggesting good generalization.
More than half of the variation in housing prices is explained by the selected features.
The model does not exhibit significant overfitting.

## Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook / Google Colab

## Learning Outcomes
Through this lab, I gained practical experience with:
Data preprocessing
Train-test splitting
Linear Regression modeling
Model evaluation using MSE
Model evaluation using R² Score
Interpreting regression performance metrics

## Author
Shivangi Jaidka
Business Analytics - Seneca Polytechnic
