# MPG Prediction Capstone Project using TensorFlow & Power BI

## Project Overview

This project is an end-to-end Machine Learning and Deep Learning capstone project focused on predicting vehicle fuel efficiency (MPG - Miles Per Gallon) using TensorFlow Neural Networks.

The project demonstrates:
- Data Cleaning & Preprocessing
- Missing Value Handling
- Feature Scaling using StandardScaler
- Train-Test Splitting
- Multi Layer Perceptron Feed Forward Neural Network
- TensorFlow Deep Learning Model
- Model Evaluation using R2 Score, MSE & RMSE
- Prediction Generation
- Power BI Dashboard Reporting
- GitHub Portfolio Deployment

---

# Business Problem

Fuel efficiency is one of the most important factors in the automobile industry.

This project aims to predict the MPG (Miles Per Gallon) of vehicles based on:
- Horsepower
- Weight
- Cylinders
- Engine Displacement
- Acceleration
- Model Year

The model helps understand:
- Which vehicles consume more fuel
- Factors affecting fuel efficiency
- Relationship between engine specifications and MPG

---

# Project Workflow

text
Dataset → Data Cleaning → Feature Scaling → Neural Network Model → Predictions → Power BI Dashboard → GitHub Portfolio


---

# Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data Processing |
| Pandas | Data Manipulation |
| NumPy | Numerical Computation |
| Scikit-Learn | Machine Learning Utilities |
| TensorFlow/Keras | Deep Learning Model |
| Google Colab | Development Environment |
| Power BI | Dashboard & Reporting |
| GitHub | Portfolio Hosting |

---

# Dataset Information

The MPG dataset contains automobile specifications and fuel efficiency data.

---

# Machine Learning Process

## 1. Data Cleaning
- Removed missing values
- Filtered invalid records
- Removed categorical columns

## 2. Feature Engineering
- Selected numerical features
- Applied StandardScaler for normalization

## 3. Train-Test Split
- 80% Training Data
- 20% Testing Data

## 4. Neural Network Architecture

Built a Multi Layer Perceptron Feed Forward Neural Network using TensorFlow.

### Model Layers
- Input Layer
- Hidden Layer (64 neurons)
- Hidden Layer (32 neurons)
- Hidden Layer (16 neurons)
- Output Layer

---

# Model Evaluation Metrics

| Metric | Purpose |
|---|---|
| R2 Score | Measures model prediction capability |
| MSE | Measures squared prediction error |
| RMSE | Measures average prediction error |

---

# Key Insights

- Lighter vehicles generally provide higher MPG.
- Higher horsepower vehicles consume more fuel.
- Vehicle weight strongly impacts fuel efficiency.
- Neural Network predictions closely match actual MPG values.
- The TensorFlow model achieved strong regression performance.

---

# Power BI Dashboard

The Power BI dashboard was created to visualize:
- Actual vs Predicted MPG
- Average MPG Analysis
- Horsepower vs MPG
- Weight vs MPG
- Fuel Efficiency Trends
- Model Prediction Insights

## Dashboard Screenshot

![Dashboard](MPG_Capstone/Project_files/Screenshot/Powerbi_Dashboard.png)

---

# Power BI Dashboard Insights

The dashboard provides analytical insights related to:
- Fuel efficiency trends
- Relationship between horsepower and MPG
- Weight impact on fuel consumption
- Actual vs Predicted MPG comparison
- Neural Network prediction performance

---

# Results

The TensorFlow Neural Network successfully predicted MPG values with strong regression performance using:
- R2 Score
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

The model predictions closely matched actual MPG values, demonstrating effective learning capability.

---

# Author

GHANGHAS MAHESH
