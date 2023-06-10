# Bike_Rental_Count_Predictio# Bike Rental Count Prediction using ML and H2O Auto ML

This repository contains code and data for a machine learning project focused on predicting bike rental counts. The project utilizes both traditional machine learning techniques and H2O Auto ML to build predictive models.

## Background

Bike sharing systems have gained significant popularity due to their convenience and positive impact on traffic, environment, and health. These systems automate the process of renting and returning bikes, making it easy for users to access bikes from various locations. This project aims to predict the bike rental count on a daily basis using environmental and seasonal settings.

## Data Set

The core data set used in this project is a two-year historical log from the Capital Bikeshare system in Washington D.C., USA. The data includes information such as date, season, weather conditions, temperature, humidity, and the count of casual and registered users. The data set is publicly available and can be accessed from [http://capitalbikeshare.com/system-data](http://capitalbikeshare.com/system-data).

## Time Line of the Project

The project follows the following steps:

1.  Importing Libraries and DataSet
2.  Data Analysis and Preprocessing
3.  Feature Engineering
4.  Model Building using ML
5.  Model Building and Prediction using H2O Auto ML

## Report

### Data Analysis

The initial data analysis involved exploring the data set, understanding its structure, and identifying relationships between variables. The data set contains various attributes such as season, year, month, hour, weather conditions, temperature, humidity, and rental counts. Visualizations were created to understand the impact of different factors on bike rental counts, including seasonal patterns, weekdays, holidays, and weather conditions.

### Data Preprocessing

Data preprocessing steps were performed to prepare the data for model building. This included handling missing values, converting data types to the appropriate category, and performing one-hot encoding for categorical variables.

### Model Building

Two models were built for this project: Linear Regression and Random Forest Regressor. The Linear Regression model used the scikit-learn library, while the Random Forest Regressor was implemented using the same library. The models were trained and evaluated using various metrics such as accuracy, root mean square error (RMSE), and mean absolute error (MAE).

### H2O Auto ML

H2O Auto ML, an open-source machine learning platform, was used to automate the model building process. The H2O Python module and H2OAutoML class were imported, and the data set was loaded into the H2O cluster. The data set was split into training and testing sets, and H2O Auto ML was applied to train multiple models using different algorithms. The leaderboard was generated to compare the performance of the models, and the best performing model was selected for further analysis.

Please note that the H2O Auto ML code provided in the README cannot be executed due to the absence of the required Java installation. To resolve this issue, please follow the instructions provided in the "Installing H2O Auto ML" section and ensure that Java is properly installed and configured on your system.

For more details and code implementation, please refer to the code files in this repository.
