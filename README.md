# Embedding-Based Deep Neural Network for Weekly Sales Forecasting 

## 1. Project Overview
This project focuses on forecasting weekly sales for retail products using an Embedding-Based Deep Neural Network. The system predicts units sold for each SKU-store combination, supporting decisions in demand planning, inventory management, and pricing strategy.

## 2. Problem Statement
Traditional forecasting models struggle to generalize across thousands of products and stores that exhibit different patterns. This leads to inaccurate predictions and ineffective stock planning.
This project aims to build a scalable deep learning model that improves prediction accuracy and adapts to changing sales behaviour

## 3. Dataset
The dataset contains weekly transactional sales data including product details, store IDs, prices, discount information, and promotional indicators. Lag features, rolling averages, and temporal features were engineered to enhance learning.

## 4. Methodology
The approach includes data preprocessing, feature engineering, log transformation for stability, and model training. The deep learning model uses categorical embeddings with dense layers to capture store- and product-level patterns. Benchmark models (Random Forest and XGBoost) were used for comparison.

## 5. Model Used
Embedding-Based Deep Neural Network

Adam optimizer and early stopping to prevent overfitting

ReLU activation, dropout, batch normalization

## 6. Results
The model achieved high forecasting accuracy and closely matched real sales patterns in visual validation. It performed competitively against traditional ML models, with improved scalability and interpretability.

## Conclusion 
The embedding-based DNN effectively predicts weekly sales by learning complex interactions among price, promotions, and time patterns. It offers a robust solution for retail forecasting and can be deployed for automated real-time decision support.

