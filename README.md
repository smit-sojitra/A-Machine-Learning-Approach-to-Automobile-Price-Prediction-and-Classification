# Automobile Price Prediction and Classification Using Machine Learning

## Project Overview

This project applies data analytics and machine learning techniques to analyse automobile data and develop predictive models for automobile price estimation and classification.

The study involves exploratory data analysis (EDA), data preprocessing, feature engineering, regression modelling, and classification modelling using Python and popular machine learning libraries.

## Dataset

The dataset used in this project is the Automobile Dataset provided through the IBM Developer Skills Network.

Dataset Source:
https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DA0101EN-SkillsNetwork/labs/Data%20files/auto.csv

The dataset contains information about vehicle specifications, performance characteristics, fuel consumption, and automobile prices.

## Objectives

- Perform exploratory data analysis (EDA)
- Handle missing values and data quality issues
- Create new features through feature engineering
- Develop regression models for automobile price prediction
- Develop classification models for automobile price category prediction
- Compare machine learning model performance
- Generate business insights and recommendations

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Tasks

### 1. Exploratory Data Analysis (EDA)

- Dataset loading and inspection
- Dataset shape analysis
- Descriptive statistics
- Data type identification
- Unique categorical value analysis
- Histograms
- Boxplots
- Correlation heatmap

### 2. Data Preprocessing

- Missing value treatment
- Data type conversion
- Feature normalization
- Feature engineering
- Horsepower binning
- Fuel consumption transformation

### 3. Regression Models

#### Linear Regression

Evaluation Metrics:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

#### Random Forest Regression

Evaluation Metrics:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

### 4. Classification Model

#### Logistic Regression

Evaluation Metrics:
- Accuracy
- Classification Report
- Confusion Matrix

## Results

### Regression Performance

| Model | MAE | MSE | R² Score |
|---------|---------|---------|---------|
| Linear Regression | 3404.43 | 24,782,385.56 | 0.797 |
| Random Forest Regression | 1799.68 | 7,862,056.71 | 0.936 |

### Classification Performance

| Metric | Value |
|----------|----------|
| Accuracy | 78.05% |

The Random Forest model achieved the best performance and was selected as the preferred model for automobile price prediction.

## Key Findings

- Curb weight is the most influential factor affecting automobile price.
- Engine size and horsepower also have a strong impact on vehicle pricing.
- Random Forest significantly outperformed Linear Regression.
- Logistic Regression successfully classified automobiles into price categories with an accuracy of approximately 78%.


## Future Improvements

- Hyperparameter optimisation
- Cross-validation
- Advanced ensemble models
- Larger and more diverse datasets
- Inclusion of additional market-related variables
