# Medical Insurance Cost Prediction using TensorFlow

## Overview
This project involves developing a predictive model for estimating medical insurance costs based on various parameters such as age, sex, BMI, children, smoking status, and residential region. The model leverages TensorFlow and a publicly available dataset from Kaggle.

## Dataset
The dataset used in this project is the [Medical Cost dataset](https://www.kaggle.com/mirichoi0218/insurance) from Kaggle. It contains the following features:
- `age`: Age of the individual
- `sex`: Gender of the individual
- `bmi`: Body Mass Index
- `children`: Number of children covered by health insurance
- `smoker`: Smoking status
- `region`: Residential region
- `charges`: Medical insurance cost (target variable)

## Project Highlights
- **Data Preprocessing**: Categorical variables were transformed using one-hot encoding.
- **Model Development**: Various machine learning techniques, including linear regression and neural networks, were implemented.
- **Optimization**: The model was optimized by adjusting layers, units, and optimizers, significantly improving performance.

## Model Performance
- Initial Mean Absolute Error (MAE): 8627.95
- Final Mean Absolute Error (MAE): 3174.24
- Improvement: Approximately 63%

## Installation
To run this project, you need to have Python and TensorFlow installed. You can install the required libraries using pip:

```bash
pip install tensorflow pandas numpy scikit-learn matplotlib
