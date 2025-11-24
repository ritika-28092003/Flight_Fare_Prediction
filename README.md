✈️ Flight Fare Prediction — Machine Learning Project

📌 Overview

Flight prices fluctuate based on multiple factors such as airline, travel date, duration, number of stops, and route.
This project builds a Machine Learning model that predicts flight fares using historical flight data, helping travelers and businesses make informed pricing decisions.

The project covers:

Data preprocessing & cleaning

Feature engineering

Exploratory data analysis (EDA)

Model training & evaluation

Performance comparison

Prediction using Random Forest Regression

🧾 Dataset

Source: CSV provided

Type: Supervised learning (Regression)

Target variable: Price

Dataset Format: Tabular flight booking information

Common Features may include:
Airline, Source, Destination, Duration, Total Stops, Date of Journey, Route, etc.


🎯 Problem Type

Regression — predicting continuous numerical values (flight fare).

🧠 Model Used

✅ Random Forest Regressor

Chosen because it:

Handles nonlinear relationships well

Works effectively with categorical + numerical features

Reduces overfitting through ensemble learning

✅ Model Performance
Metric	                         Score
Mean Absolute Error (MAE)	1180.33
Mean Squared Error (MSE)	4,395,384.82
R² Score	                  0.796

The model explains ~79.6% of the variance in flight prices — strong performance for real-world airfare prediction.

📊 Exploratory Data Analysis Included

Missing value treatment

Airline-wise price comparison

Duration vs fare relationship

Correlation heatmap

Category distribution visualizations

Outlier detection

🛠️ Tech Stack

Python

Jupyter Notebook

Pandas

NumPy

Matplotlib / Seaborn


Scikit-learn
