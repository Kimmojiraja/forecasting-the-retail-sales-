Sales Forecasting Using Machine Learning

This project demonstrates a comprehensive approach for predicting weekly unit sales using machine learning and deep learning techniques. The workflow includes data preprocessing, feature engineering, exploratory data analysis, and the implementation and evaluation of several predictive models. The key objectives are to analyze historical sales data, uncover feature importance, and provide accurate forecasting for business decision support.
Key Features
Cleans and processes transactional sales data containing store-level and SKU-level information.

Explores weekly and store-wise trends in sales and revenue using data visualization.

Implements multiple predictive models:

Random Forest Regression

XGBoost Regression

LSTM-based Deep Learning

Compares and evaluates models using metrics such as MSE, MAE, and 
R
2
R 
2
  score.

Highlights feature importance for actionable business insights.

Designed for robust forecasting to guide inventory and promotion planning.


Usage
Requires Python and Jupyter Notebook environment.

Libraries: pandas, numpy, scikit-learn, xgboost, seaborn, matplotlib, tensorflow/keras.

To run, open the notebook and execute cells sequentially, ensuring all dependencies are installed.

Includes code for data preparation, model training, and visual analysis of predictions.

Project Structure
Data ingestion and preprocessing.

Exploratory Data Analysis (EDA).

Feature engineering for regression tasks.

Model development with Random Forest, XGBoost, and LSTM.

Model evaluation and result visualization.

Results
Random Forest and XGBoost both show high accuracy for sales forecasting, with LSTM providing an alternative sequence-based approach.

Feature importance analysis reveals ‘revenue per unit’ and ‘discount percentage’ as key drivers in sales predictions.

Visualizations and prediction plots provide business insights for scaling or optimizing sales strategies.

