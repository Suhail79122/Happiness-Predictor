# Happiness Predictor using Linear Regression

## Overview
This project focuses on predicting people's happiness scores using a machine learning approach based on Linear Regression. It analyzes various socio-economic factors to understand their impact on overall life satisfaction.

## Problem Statement
Happiness is influenced by multiple economic and social indicators. The goal of this project is to build a predictive model that estimates happiness scores based on measurable features.

## Dataset
The dataset includes the following features:
- GDP per capita
- Social support
- Healthy life expectancy
- Freedom to make life choices
- Generosity
- Perceptions of corruption

Target variable:
- Happiness Score

## Methodology
1. Data loading and preprocessing  
2. Feature selection and target definition  
3. Splitting the dataset into training and testing sets  
4. Training a Linear Regression model  
5. Evaluating performance using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
   - R² Score  
6. Visualizing actual vs predicted results  

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Results
The model provides reasonable predictions of happiness scores based on the selected features. Performance evaluation metrics indicate the effectiveness of the regression model in capturing relationships within the data.

## How to Run

1. Install dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib
```

2. Run the project:
```bash
python main.py
```

## Future Improvements
- Try advanced models such as Random Forest and XGBoost  
- Improve feature engineering  
- Optimize model performance  
- Add a user interface  

## Author
This project was developed as part of a Machine Learning course assignment.
