# House Price Prediction

## Overview
This project aims to predict house prices using machine learning techniques, offering valuable insights into the real estate market. By analyzing features like size, location, and construction quality, we provide an accurate model to assist stakeholders such as homeowners, buyers, and investors.

## Abstract
The real estate market plays a vital role in the economy. Traditional methods of house price prediction often fail to capture the complex relationships among factors influencing house prices. Leveraging machine learning, we analyzed large datasets to uncover patterns, enhancing prediction accuracy and enabling informed decision-making.

## Models and Techniques
We utilized the following models:

### Linear Models
1. **Linear Regression**: Baseline model to assess other techniques.
2. **Elastic Net Regression**: Combines L1 and L2 penalties to improve performance on datasets with multicollinearity.
3. **Ridge Regression**: Incorporates L2 regularization for better generalization.
4. **Bayesian Ridge Regression**: Introduces probabilistic inference to handle uncertainty.

### Non-Linear Models
1. **Support Vector Regression (SVR)**: Captures non-linear relationships.
2. **Random Forest Regressor**: Builds an ensemble of decision trees for better accuracy.
3. **XGBoost**: An advanced boosting algorithm for high accuracy.
4. **Stochastic Gradient Descent Regressor (SGD)**: Efficient for large datasets with L1 or L2 regularization.

## Results
| Model               | Mean Squared Error (MSE) | Root Mean Squared Error (RMSE) | Mean Absolute Error (MAE) |
|---------------------|---------------------------|--------------------------------|---------------------------|
| Linear Regression   | 1.12 × 10^30            | 1.06 × 10^15                 | 1.13 × 10^14            |
| SVR                 | 7.18 × 10^9             | 84,754.2                      | 57,181.6                 |
| Elastic Net         | 2.45 × 10^9             | 49,514.2                      | 30,173.1                 |
| Random Forest       | 7.21 × 10^8             | 26,865.4                      | 16,576.2                 |
| **XGBoost**         | **6.84 × 10^8**         | **26,164.8**                  | **17,069.1**             |
| SGD                 | 9.67 × 10^8             | 31,082.5                      | 20,326.9                 |
| Ridge Regression    | 8.17 × 10^8             | 28,593.6                      | 18,910.5                 |
| Bayesian Ridge      | 8.65 × 10^8             | 29,419.3                      | 19,380.4                 |

**Conclusion:** XGBoost demonstrated the highest accuracy, with the lowest RMSE and MAE values.

For detailed methodology, refer to the full documentation in this repository. Feedback and contributions are welcome!

