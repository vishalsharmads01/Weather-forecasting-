# Weather-forecasting-
SkyCast – Weather Forecasting & Rain Prediction System

SkyCast is a Python-based weather analytics system that leverages real-time weather data and machine learning techniques to predict rainfall and short-term atmospheric conditions such as temperature and humidity.

The system integrates live data from the OpenWeatherMap API and applies Random Forest models to deliver reliable predictions based on historical weather patterns

Project Objectives

To fetch and process real-time weather data for user-specified locations

To predict the likelihood of rainfall using supervised machine learning

To forecast short-term temperature and humidity trends

To demonstrate practical application of data preprocessing and ML models

Key Features

Real-time weather data retrieval using external API

Rain prediction using Random Forest Classification

Short-term temperature and humidity forecasting using regression models

Data cleaning, encoding, and feature engineering

Command-line based user interaction

Technologies & Tools

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Requests, pytz

Machine Learning Models:

RandomForestClassifier

RandomForestRegressor

API: OpenWeatherMap

System Workflow

User enters a city name

Real-time weather data is fetched via API

Historical data is cleaned and preprocessed

Machine learning models are trained

Rain prediction and future weather forecasts are generated

Results are displayed in the console

Dataset

Historical weather data stored in weather.csv

Dataset preprocessing includes:

Removal of missing values

Removal of duplicate records

Encoding of categorical attributes

Installation & Execution
Install Required Dependencies
pip install requests pandas numpy scikit-learn pytz

Configure API Key
export OPENWEATHER_API_KEY="your_api_key"

Model Description

Rain Prediction:
Supervised classification using Random Forest based on meteorological features such as temperature, humidity, wind direction, wind speed, and pressure.

Temperature & Humidity Forecasting:
Regression models trained on historical time-series data to predict short-term future values.

Future Enhancements

Long-term (7–15 days) weather forecasting

Integration with a web-based dashboard

Visualization using charts and graphs

Model optimization and performance evaluation

Deployment as a full-stack weather application

Author

Baby
Aspiring Data Scientist

