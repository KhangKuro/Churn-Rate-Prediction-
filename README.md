<img src = "https://github.com/KhangKuro/Churn-Rate-Prediction-/blob/main/picture.png" />

# Churn Rate Prediction Project 📉

## Overview ℹ️

Churn rate prediction is a crucial task in marketing analytics that aims to identify customers who are likely to leave a business over a specific time period. This project focuses on developing a machine learning model to predict churn rates using various customer attributes and behaviors.

## Team Members 👥

- Huynh Bao Khang
- Dang Yen Linh 
- Nguyen Ngoc Son 
- Nguyen Van Son 

## Requirements 🛠️

- Python 3.x
- Libraries: pandas, numpy, seaborn, matplotlib.pyplot, sklearn, imblearn, xgboost
- Jupyter Notebook or any other Python IDE

## Dataset 📊

The dataset used in this project is stored in `churn_rate_prediction.csv`. It contains various customer attributes such as demographic information, browsing behavior, historical purchase data, and churn risk scores. The dataset includes both numerical and categorical features.

## Project Structure 📂

The project is organized as follows:

1. **Data Preparation and Analysis**: This section involves loading the dataset, examining its dimensions, identifying unique values for each feature, and analyzing statistics of null and missing values.

2. **Model Building**: We utilize machine learning techniques to build predictive models for churn rate prediction. This includes data preprocessing, feature engineering, model training using algorithms such as Support Vector Machines (SVM), and evaluation using various metrics.

3. **Model Evaluation**: We evaluate the performance of the models using metrics such as accuracy, precision, recall, F1-score, confusion matrices, and classification reports. We compare the results of SVM models with and without oversampling techniques.

4. **Principal Component Analysis (PCA)**: We perform PCA to visualize the data in reduced dimensions (2D and 3D) and observe the distribution of churn risk scores within the dataset.

## Model Performance and Analysis 📈

- We analyze the performance of the SVM model with and without oversampling techniques. 
- Confusion matrices provide detailed insights into how the model predicts different churn risk scores and highlight areas of improvement.
- PCA visualizations help in understanding the data's structure and potential clusters.

## Conclusion 🎯

- The primary metric for evaluating model performance is weighted average recall due to class imbalance in the dataset.
- The project aims to identify customers at risk of churn to facilitate retention efforts and improve customer satisfaction.

## Instructions for Running the Code 🏃‍♂️

1. Install Python 3.x and required libraries.
2. Clone the repository to your local machine.
3. Navigate to the project directory.
4. Run the Jupyter Notebook or Python scripts to execute the code.

## Disclaimer ⚠️

This study is intended for educational purposes only. The analysis and findings presented here are based on simulated data and should not be used for any commercial purposes or real-world decision-making without proper validation and authorization.

