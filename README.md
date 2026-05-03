ر# Happiness Predictor using Linear Regression

## Overview
This project focuses on predicting people's happiness scores using a machine learning approach based on Linear Regression. It analyzes various socio-economic factors to understand their impact on overall life satisfaction.

## Problem Statement
Happiness is influenced by multiple economic and social indicators. The goal of this project is to build a predictive model that estimates happiness scores based on measurable features.

## Dataset
The dataset used in this project is included in this repository:

- `2020.csv`

It contains socio-economic features such as GDP per capita, social support, healthy life expectancy, freedom, generosity, and perceptions of corruption, which are used to predict happiness scores.

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

## Code

The implementation of this project is available in the repository.

Example:

```python
import pandas as pd
from sklearn.linear_model import LinearRegression

df = pd.read_csv("2020.csv")

X = df[[
    "GDP per capita",
    "Social support",
    "Healthy life expectancy",
    "Freedom to make life choices",
    "Generosity",
    "Perceptions of corruption"
]]
y = df["Score"]

model = LinearRegression()
model.fit(X, y)
```

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Results
The model achieved good performance based on evaluation metrics such as MAE, MSE, RMSE, and R² score.  
The visualization of actual vs predicted values shows a strong correlation, indicating that the model fits the data reasonably well.


## How to Run

1. Install dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib notebook
```

2. Open the notebook:
```bash
jupyter notebook
```

3. Run the file:
- Open `Happiness_Predictor.ipynb`
- Run all cells

## Future Improvements
- Try advanced models such as Random Forest and XGBoost  
- Improve feature engineering  
- Optimize model performance  
- Add a user interface  

Notebook file: Happiness_Predictor.ipynb

## Author
Suhail – AI System Engineering Student
