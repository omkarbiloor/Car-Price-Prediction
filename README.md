# Car Price Prediction 🚗💰

This repository contains a machine learning project that predicts car prices based on various features such as brand, model, fuel type, engine specifications, and more. The project utilizes a dataset to train a regression model, aiming to provide accurate price estimates.

## 📊 Project Overview

The **Car Price Prediction** project helps estimate car prices using historical data and machine learning techniques. It can assist individuals and businesses in understanding the key factors influencing car prices and provide insights for better decision-making.

### Key Features:
- **Data Preprocessing**: Cleaning and preparing data for analysis.
- **Feature Engineering**: Selecting relevant features that influence car prices.
- **Model Training**: Building and fine-tuning regression models.
- **Evaluation**: Measuring model performance using metrics like RMSE and MSE.

---

## 📁 File Structure

- **`CAR PRICE PREDICTION.ipynb`**: Jupyter Notebook containing code and analysis.
- **Dataset**: 
  - **`CarPrice_Assignment.csv`**: The dataset used in this project (example structure detailed below).
- **README.md**: Documentation for the project.

---

## 🔧 Requirements

- Python 3.7 or later
- Libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `jupyter`


## 📊 Dataset Description

The dataset (`car_prices.csv`) includes the following features:

| **Feature Name**   | **Description**                                      |
|---------------------|------------------------------------------------------|
| **Car Model**       | The specific model of the car (e.g., Civic, Corolla).|
| **Brand**           | Manufacturer or brand of the car (e.g., Honda, Ford).|
| **Year**            | Manufacturing year of the car.                      |
| **Fuel Type**       | Type of fuel used (e.g., Petrol, Diesel, Electric). |
| **Engine Type**     | Engine specification (e.g., V6, V8, Turbo).         |
| **Mileage**         | Mileage of the car in km/l or mpg.                  |
| **Price**           | Selling price of the car (Target variable).         |

---

## 📈 Models Used

- **Linear Regression**
---

## 📜 Results

- Model Performance:
  - **MSE Score**: 18901997.60241035
  - **Root Mean Square Error (RMSE)**: 53.587565702924174
---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

