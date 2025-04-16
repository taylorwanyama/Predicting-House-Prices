# House-prices
# Predicting House Prices using Machine Learning

## Overview

This project applies a machine learning technique (Linear Regression) to predict house prices using various features such as house age, proximity to MRT stations, number of convenience stores, and geographic coordinates.

## Dataset

The dataset used is **Real\_estate\_dataset.csv**, which contains the following features:

- `transaction_date`: The date of the house sale.
- `house_age`: Age of the house in years.
- `distance_to_MRT`: Distance from the house to the nearest MRT station.
- `num_convenience_stores`: Number of convenience stores nearby.
- `latitude`: Latitude coordinate of the house.
- `longitude`: Longitude coordinate of the house.
- `house_price`: The target variable (price of the house).

## Steps in the Project

1. **Data Preprocessing**
   - Checked for missing values and data types..
2. **Exploratory Data Analysis (EDA)**
   - Visualized relationships between variables.
   - Checked for correlations to identify key influencing factors.
3. **Model Selection & Training**
   - Implemented **Linear Regression** as the baseline model.
   - Performed **Hyperparameter tuning** using **Ridge Regression**.
   - Evaluated models using metrics like **MAE and MSE**.
4. **Results & Conclusion**
   - The best-performing model was found to be **Linear Regression** with minimal improvement using Ridge Regression.
   - The equation for predicting house prices using Linear Regression is:

     $$
     \text{House Prices} = -14866.72 + 5.02 \times \text{(transaction date)}  
     - 0.263 \times \text{(house age)}  
     - 0.00446 \times \text{(distance to nearest MRT station)}  
     + 1.09 \times \text{(number of convenience stores)}  
     + 225.49 \times \text{(latitude)}  
     - 6.81 \times \text{(longitude)}
     $$

## Dependencies

To run this project, install the following libraries:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn
```

## Running the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/taylorwanyama/Predicting-House-Prices/blob/main/Predicting%20House%20Prices%20final%20(1).ipynb
   ```
2. Open the Jupyter Notebook and run the cells sequentially.
3. Modify parameters and visualize results for deeper analysis.

## Future Improvements

- Apply **Lasso Regression** for feature selection.
- Experiment with **Polynomial Regression** to capture non-linearity.
- Use XGBoost in Predicting the House Prices.
- Add **Cross-Validation** to improve model robustness.
- Normalize features to improve Ridge Regression performance.

## Author

[Taylor Wanyama] - Aspiring Data Scientist


