# Raisin Classification Using Supervised Machine Learning Techniques

## Overview
This project focuses on the binary classification of raisins into two categories: Besni and Kecimen. It involves exploratory data analysis (EDA), preprocessing, feature engineering, model training, evaluation, and comparison of different machine learning algorithms.

## Objectives
- Gain insight into the dataset and its features.
- Clean and preprocess the data for effective modelling.
- Conduct feature engineering.
- Apply logistic regression algorithms to differentiate between raisin varieties.
- Optimize model performance by tuning hyperparameters and emphasizing key features.
- Evaluate the performance of logistic regression against other classification algorithms.
  
## About the Dataset
The dataset comprises two varieties of raisins (Keçimen and Besni) grown in Turkey. Images of these two raisin types were sourced using CVS. A total of 900 raisin grains were included in the dataset, with 450 samples from each variety. The images underwent multiple preprocessing steps, and seven morphological features were extracted for analysis.

- **Dataset**: Raisin Grain
- **Content**: Besni (0) and Kecimen (1)
- **Number of Rows**: 900
- **Number of Columns**: 8

## Table of Contents
1. Exploratory Data Analysis (EDA)
2. Data Cleaning
    - Missing Values
    - Duplicated Values
4. Statistical Overview
    - Basic Statistics
    - Categorical Features
    - Numerical Features
5. Feature Engineering
6. Correlation Analysis
7. Outlier Analysis
8. Modelling
    - Logistic Regression
    - Model Performance
    - Model Validation
    - Hyperparameter Optimization
    - Support Vector Machine
    - K-Nearest Neighbors
    - Decision Tree Classifier
9. Comparison of Models

### 1. Exploratory Data Analysis (EDA)
- Loaded the dataset and examined its dimensions and initial records
- Dataframe shape: df.shape
- Displayed first and last few rows: df.head() and df.tail()

### 2. Data Cleaning
#### Missing Values
- There are no missing values detected in the dataset.

#### Duplicated Values
- Checked for duplicates and confirmed there are none.

### 3. Statistical Overview
#### Basic Statistics
- Provided summary statistics of the dataset, showing data types and distributions.

#### Categorical Features
- Class distribution: df.Class.value_counts()

#### Numerical Features
- Visualized distributions of numerical features using histograms.

### 4. Feature Engineering
- Converted class labels to numerical values using label encoding.
- Dropped the original class label from the dataset.

### 5. Correlation Analysis
- Analyzed correlations among features and with the target variable.
- Identified highly correlated features and their implications for modeling.

### 6. Outlier Analysis
- Conducted outlier detection using box plots for individual features and by target class.

### 7. Modeling
#### Logistic Regression
- Split dataset into training and testing sets.
- Trained logistic regression model using Min-Max scaling.

#### Model Performance
- Evaluated model using accuracy, confusion matrix, and classification report.

#### Model Validation
- Conducted cross-validation to assess model reliability.

#### Hyperparameter Optimization
- Tuned logistic regression hyperparameters using GridSearchCV for improved accuracy.

#### Support Vector Machine
- Implemented SVM and evaluated performance.

#### K-Nearest Neighbors
- Tested various neighbor counts to determine optimal k.

#### Decision Tree Classifier
- Trained a decision tree model and evaluated its performance.

### 7. Comparison of Models
- Compared accuracy scores of all models visually using bar plots.

[Result of Machine Learning Models]()
