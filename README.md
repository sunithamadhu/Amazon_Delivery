🚚 E-Commerce Delivery Time Prediction
Predicting delivery times for e-commerce orders based on multiple factors like distance, traffic, weather, and product category. This project involves end-to-end development of a machine learning system that helps enhance logistics and customer satisfaction through accurate delivery time estimates.

📌 Table of Contents
📖 Project Overview

📊 Business Use Cases

⚙️ Approach

📁 Dataset

🔍 Exploratory Data Analysis (EDA)

📈 Model Development

🌐 Application Interface

📦 Deployment

🧪 Results

🛠️ Tech Stack

📁 Project Structure

🧑‍💻 Contributors

📄 License

📖 Project Overview
This project aims to build a machine learning system that predicts delivery times of e-commerce orders using data about agents, weather, traffic, and geographical information. The final product includes a Streamlit web application where users can input order details and receive a delivery time estimate in real-time.

📊 Business Use Cases
Enhanced Delivery Logistics: Improve customer satisfaction with accurate delivery estimates.

Dynamic Adjustments: Adjust ETAs based on live weather and traffic data.

Agent Performance Monitoring: Evaluate delivery agent efficiency.

Operational Efficiency: Optimize resource allocation and delivery schedules.

⚙️ Approach
🔹 Data Preparation
Load dataset (amazon_delivery.csv)

Handle missing values, duplicates

Feature engineering:

Calculate distance between store and drop locations

Extract date and time components

🔹 Data Cleaning
Standardize categorical values (weather, traffic, vehicle type)

Impute or drop missing data

Remove outliers and irrelevant columns

🔹 Exploratory Data Analysis (EDA)
Analyze the distribution of delivery times

Identify trends in agent performance, weather, and traffic conditions

Visualize data with matplotlib/seaborn

🔹 Feature Engineering
Geospatial distance using Haversine formula

Time-based features (hour, day of week, etc.)

One-hot encoding of categorical features

🔹 Model Development
Train and compare:

Linear Regression

Random Forest Regressor

Gradient Boosting Regressor

Evaluation metrics:

RMSE, MAE, R² Score

Model tracking using MLflow

