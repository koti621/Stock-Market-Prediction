# Stock Market Prediction 📈

## Overview
This project uses **machine learning** techniques to analyze and predict stock market movements using Tesla (TSLA) stock data. It employs **data visualization, feature engineering**, and multiple classification models.

## Features
- **Data Preprocessing**: Cleans and structures stock data.
- **Exploratory Data Analysis (EDA)**: Uses **Seaborn** and **Matplotlib** for trend visualization.
- **Feature Engineering**: Extracts important time-based trends.
- **Machine Learning Models**: Implements **Logistic Regression, SVM, and XGBoost** for stock trend classification.

## Installation
To run this project, install the required dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
Usage
- Load the Stock Data:
- The dataset (TSLA.csv) should be in the project folder.
- Ensure paths are correct when reading the CSV file.
- Run the Prediction Script:
python stock_market_prediction.py


- This script processes stock data and applies machine learning models.
Code Explanation- Data Loading: Reads historical TSLA stock prices.
- Preprocessing:
- Cleans missing values.
- Extracts day, month, and year from date.
- Visualization:
- Plots closing price trends.
- Uses distribution plots & boxplots for stock behavior analysis.
- Feature Engineering:
- Computes quarter-end indicators for trend insights.
- Model Training:
- Uses Logistic Regression, SVM, and XGBoost for classification.
Example Output- The system visualizes stock trends and predicts movement direction.
Future Enhancements- Implement deep learning models like LSTMs for time-series forecasting.
- Include more stock market datasets for broader predictions.
License
