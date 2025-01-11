# Sales Forecasting Project

## Overview

This project is aimed at forecasting sales using advertising spend data on TV, radio, and newspaper. The model predicts future sales based on past advertising campaigns. It is a beginner-level project that demonstrates the use of machine learning regression techniques, data visualization, and basic exploratory data analysis.

## Table of Contents
- [Project Overview](#overview)
- [Technologies Used](#technologies-used)
- [Data Description](#data-description)
- [Model Explanation](#model-explanation)
- [Visualization](#visualization)
- [Model Performance](#model-performance)
- [Conclusion](#conclusion)

## Technologies Used

- Python
- Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, Tkinter
- Jupyter Notebook / Python IDE

## Data Description

The dataset contains the following columns:
- **TV**: Advertising spent on TV in thousands.
- **Radio**: Advertising spent on Radio in thousands.
- **Newspaper**: Advertising spent on Newspaper in thousands.
- **Sales**: The actual sales outcome in thousands of units.

The data can be downloaded from the following URL:  
[Sales Advertising Data](https://raw.githubusercontent.com/selva86/datasets/master/Advertising.csv)

## Model Explanation

1. **Data Loading**: The dataset is loaded using the pandas library for data manipulation.
2. **Data Preprocessing**: Data cleaning (if required) and preparing the dataset for training by splitting it into features (X) and target (Y).
3. **Model Training**: A linear regression model is used to train on the dataset, predicting the sales based on advertising spend.
4. **Model Testing**: The data is split into training and testing sets using `train_test_split`, with a test size of 0.2.
5. **Prediction**: The model predicts sales on the test dataset and is compared with actual sales.

## Visualization

The following visualizations demonstrate the model's performance:

- **Actual Sales vs Predicted Sales**
  - Here, we visualize how well the model predicts the sales based on advertising spend.

![Salary Prediction Plot](https://github.com/Hritik0052/Sales-Forecasting-Linear_Model/blob/main/salary_prediction_plot.png)

- **Feature Importance**
  - We will also explore the relationships between advertising spends on different mediums (TV, radio, and newspaper) and how they affect sales.

![Correlation Matrix](https://github.com/Hritik0052/Sales-Forecasting-Linear_Model/blob/main/Corr.png)



## Model Performance

We evaluate the performance of our model using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared score. These help to determine how well the model fits the data and predicts future sales.

### Example:
