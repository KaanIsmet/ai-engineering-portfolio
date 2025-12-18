# Gas Consumption Prediction Project

## Overview
This project analyzes gas consumption data and builds predictive models using machine learning techniques to forecast gas usage based on various features. 
The implementation includes data cleaning, exploratory data analysis, and two regression approaches: **Random Forest Regressor** and **Linear Regression with Polynomial Features**.



---

## Key Features

- Data cleaning and preprocessing  
- Outlier detection and removal using IQR method  
- Exploratory data analysis with visualizations  
- Two predictive modeling approaches:
  - Random Forest Regressor
  - Polynomial Regression with Linear Regression  
- Model evaluation metrics:
  - Mean Squared Error (MSE)
  - R-squared score
  - Coefficient analysis

---

## Technologies Used

- **Python 3**
- **Jupyter Notebook**
- **Pandas** – Data manipulation
- **NumPy** – Numerical computing
- **Matplotlib / Seaborn** – Data visualization
- **Scikit-learn** – Machine learning models
  - `RandomForestRegressor`
  - `LinearRegression`
  - `PolynomialFeatures`

---

## Data

The dataset (`GasConsumption.csv`) contains gas consumption records with the following key features:
- **Current Charges**
- **Consumption (Therms)**
- **Number of Days**

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/gas-consumption-prediction.git
cd gas-consumption-prediction
```
Create and activate a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

