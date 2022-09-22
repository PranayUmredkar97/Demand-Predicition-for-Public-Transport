# **Demand-Predicition-for-Public-Transport**
## **Build a model that predicts the number of seats that Mobiticket can expect to sell for each ride, i.e. for a specific route on a specific date and time.**

Tags: Data Science, Data Analysis, Machine Learning, Linear Regression,Random Forest

![chuttersnap-kq8iWoh5-mU-unsplash (1)](https://user-images.githubusercontent.com/71922973/190112251-a2ff11a8-cb04-464c-9ead-196bb5a6c27a.jpg)

### **Summary**

Public transport is an effective tool to address multiple societal challenges, regarding mobility, sustainability and livability. In this report we are going to study how Mobiticket a ticket booking platform can expect a number of bookings on a particular day and time.
We are provided with the data of travel patterns of different cities which ends in Nairobi. We are building a regression model to help Mobiticket to predict number of tickets can sell on each ride.

In this project We had presented my analysis of data and  We had used various regression algorith to predict number of tickets namely.

1. Linear Regression
2. Ridge and Lasso
3. Gradient Boosting
4. XGBoost

We followed step by step process for the project like data collection, data cleaning, EDA, Visualization, Model Training and Testing, Hyperparameter Tuning and Evaluation.

**Data collection and Processing**

In the first step we collected data and explored data set to get a rough idea about data. In data wrangling process on raw data, formatted data type of columns and added some columns for our analysis. 

In this data the target variable was not given so we calculated Target variable by grouping data by ride and counted number of tickets for each ride id.

**EDA**

In EDA we divided analysis into several part to get better idea about data we checked month and days wise travel patterns, at what time of day people travel most etc. We used bar plot to check travel patterns of traveller from cities, month wise, day wise, year wise and weekend wise. Pie Chart to check which type of vehicle is used mostly for transportation, checked relationship of vehicle type and target variable also check relationship of travel time with target variable with respect to vehicle type.

**Feature Engineering**

After that we perform feature engineering, in feature engineering we created some new feature form available features with the goal of simplifying and speeding up data transformation while also improving model performance.

After feature engineering we selected feature to use to train our model and encoded categorical variables as ML model works with numerical data to do computation. We used label encoding and one hot encoding.

**Model training and testing**

As data is ready, we trained different model to check their performances and performed hyperparameter tuning to improve their performances by GridsearchCV technique. Out of all the model XGboost models gives the best performance.

Model Performance:

![WhatsApp Image 2022-09-22 at 2 25 23 PM](https://user-images.githubusercontent.com/71922973/191704045-dd6c5a1d-7c37-44ca-804f-4ead34c90c15.jpeg)


