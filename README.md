# Personal Cost Forecast

## Project Description
This project focuses on predicting the target variable "charges" by employing Linear Regression with a dataset containing 7 variables. The objective was to identify the most influential feature in predicting charges. To achieve this, the following steps were taken:

1-Model Creation from Scratch:
The Linear Regression model was built entirely from scratch, providing a hands-on understanding of the underlying principles.

2-Feature Selection:
Six different models were created, each utilizing a different feature alongside the target variable. The cost function was calculated for each model, and the feature resulting in the lowest cost function was selected as the primary predictor.

## Key Features
- Implementation of Linear Regression from scratch.
- Feature selection based on cost function comparison.
- Utilization of a dataset with 7 variables, targeting the "charges" variable.

## Mathematical Formulas
1. **Linear Regression Model:**
   - The equation of the linear regression model is given by:
      $ y = w * x + b $

2. **Cost Function**
   - The function is defined as:
      $ J(w, b) = (1 / n) * Σ (yᵢ - w * xᵢ - b)   for i from 0 to 1337 ( xi: feature and yi: target) $

3. **Gradient Descent**
   - The derivative of the cost function with respect to w is defined as:
      $ dJ_dw = (-2 / n) * Σ xi * (yᵢ - w * xᵢ - b)   for i from 0 to 1337. $
   - The derivative of the cost function with respect to b is defined as:
      $ dJ_dw = (-2 / n) * Σ (yᵢ - w * xᵢ - b)   for i from 0 to 1337. $
   - The algorithm is defined as:
      $ w = w - L * dJ_dw $
      $ b = b - L * dJ_db $
     L is the learning rate.

## Technologies Used
The model is implemented in Python, leveraging the Pandas library for data cleaning and preparation, and utilizing Matplotlib for visualizing the results.
     
## About the Author
Feel free to connect with me and explore more of my work.

- [Kaggle Profile](https://www.kaggle.com/badrlakhal)
- [LinkedIn Profile](https://www.linkedin.com/in/badr-lakhal-721603276/)












