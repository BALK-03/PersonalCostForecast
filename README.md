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
     
      $$ y = w * x + b $$
2. **Cost Function:**

The cost function is defined as:

\[ J(w, b) = \frac{1}{n} \sum_{i=0}^{1337} (y_i - w \cdot x_i - b) \quad \text{for } i \text{ from 0 to 1337} \]

where \( x_i \) represents the feature and \( y_i \) represents the target.

3. **Gradient Descent:**

The derivative of the cost function with respect to \( w \) is defined as:

\[ \frac{dJ}{dw} = \frac{-2}{n} \sum x_i \cdot (y_i - w \cdot x_i - b) \quad \text{for } i \text{ from 0 to 1337} \]

The derivative of the cost function with respect to \( b \) is defined as:

\[ \frac{dJ}{db} = \frac{-2}{n} \sum (y_i - w \cdot x_i - b) \quad \text{for } i \text{ from 0 to 1337} \]

The algorithm is defined as:

\[ w = w - L \cdot \frac{dJ}{dw} \]
\[ b = b - L \cdot \frac{dJ}{db} \]

where \( L \) is the learning rate.

## Technologies Used
The model is implemented in Python, leveraging the Pandas library for data cleaning and preparation, and utilizing Matplotlib for visualizing the results.
     
## About the Author
Feel free to connect with me and explore more of my work.

- [Kaggle Profile](https://www.kaggle.com/badrlakhal)
- [LinkedIn Profile](https://www.linkedin.com/in/badr-lakhal-721603276/)












