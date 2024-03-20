# Project Name

This project is developed to analyze the closing prices of companies in different sectors in the stock market and to build a model to predict these values.

## Purpose

The purpose of this project is to analyze and predict the closing prices of companies in various sectors of the stock market. These predictions can be used to provide insights into future price movements for investors.

## Data and Technologies Used

- Data Source: Closing prices of stocks and company sector information obtained through web scraping
- Libraries Used:
  - yfinance
  - pandas
  - numpy
  - requests
  - BeautifulSoup
  - sklearn
  - tsfresh
  - seaborn
  - matplotlib
  - scipy
  - feature_engine
- Modeling Algorithms:
  - Logistic Regression
  - Random Forest
  - XGBoost
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
  - Multi-layer Perceptron (MLP)

## Data Preparation and Preprocessing

1. Closing prices of stocks and company sector information were scraped from the web.
2. Data cleaning was performed, and missing values were filled.
3. Outliers were identified and attempted to be corrected.
4. Data features were scaled and transformed.

## Model Development

1. Data was split into training and test sets.
2. Multiple models (Logistic Regression, Random Forest, XGBoost, SVM, KNN, MLP) were trained.
3. Model performance was evaluated, and the best model was selected.

## Results

Key results obtained from the project include:

- Best-performing model: [Logistic Regression]
- Accuracy rate achieved on the test set: 78%
- Performance metrics such as Confusion Matrix, Precision, Recall, F1 Score: [Metric values]
