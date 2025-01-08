# Air Quality Prediction

## Project Overview
Air quality has become a critical concern in urban and industrial areas due to increasing pollution levels. This project aims to predict air quality by analyzing the concentration of pollutants such as SO2, NO2, and CO. The model leverages machine learning techniques to forecast pollutant levels and provide insights that can help mitigate the impact of poor air quality on human health and the environment.

## Problem Statement
The goal of this project is to predict air quality and assess the risk of diseases that can be caused by air pollution. The model estimates pollutant concentrations and forecasts air quality indices (AQI) based on environmental data.

## Dataset
The dataset used for this project was sourced from the UCI Machine Learning Repository. It consists of 9358 instances of hourly averaged responses from an array of metal oxide chemical sensors deployed in an Italian city. The dataset includes:
- PM2.5
- PM10
- NO2
- NH3
- SO2
- CO
- Ozone
- Air Quality Index (AQI)

## Methodology
The project follows these key steps:
1. **Data Collection**: Real-time data was collected from air quality sensors deployed in urban areas.
2. **Data Pre-processing**: Data cleaning, handling missing values, and transforming raw data into numerical values.
3. **Visualization**: Box plots and correlation matrices were used to analyze and visualize pollutant distributions and relationships.
4. **Modeling**:
   - **Linear Regression**: To model relationships between pollutants and predict AQI.
   - **Decision Tree**: For non-linear predictions of air quality.
   - **K-Nearest Neighbors (KNN)**: For regression-based AQI predictions.
   - **Random Forest**: An ensemble learning technique to improve prediction accuracy.
   - **Support Vector Machine (SVM)**: To handle non-linear patterns in the dataset.
5. **Model Evaluation**: Models were evaluated using metrics such as Mean Square Error (MSE), Mean Absolute Error (MAE), and Root Mean Square Error (RMSE).

## Results
- **Linear Regression**:
  - MSE: 20.19
  - MAE: 3.61
- **Decision Tree**:
  - MSE: 12.02
  - MAE: 2.11
- **Random Forest**:
  - MSE: 6.25
  - MAE: 1.61
- **Support Vector Machine**:
  - MSE: 24.14
  - MAE: 3.67

The Random Forest model achieved the best performance with the lowest error rates.

## Future Scope
- Integration with IoT sensors for real-time air quality monitoring.
- Expansion of the dataset to cover larger geographic areas.
- Implementation of deep learning models for improved accuracy.

## Installation and Usage
1. Clone the repository:


Copy code
2. Install dependencies:
pip install -r requirements.txt

Copy code
3. Run the project:
