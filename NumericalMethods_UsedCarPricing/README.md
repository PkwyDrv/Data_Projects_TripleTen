# Used Car Price Prediction Using Boosting and Optuna

This project aims to predict the prices of used cars based on various features using boosting algorithms and hyperparameter optimization with Optuna. The objective is to build an accurate predictive model that can estimate used car prices, providing valuable insights for buyers, sellers, and dealerships.

## Project Overview

The Jupyter notebook demonstrates the complete workflow for predicting used car prices, including:
- Data preprocessing and feature engineering
- Training boosting models, such as Gradient Boosting and XGBoost
- Hyperparameter tuning using Optuna for model optimization
- Evaluating model performance to ensure accurate price predictions

## Dataset

The dataset used in this project contains information about used cars, such as:
- Vehicle features (e.g., make, model, year, mileage, engine size)
- Pricing details (e.g., selling price, original price)
- Additional attributes (e.g., fuel type, transmission, number of doors)

The data is utilized to train machine learning models that predict the selling price of used cars based on the provided features.

## Key Objectives

- **Predict used car prices:** Build machine learning models to estimate the prices of used cars based on their attributes.
- **Optimize model performance:** Use Optuna for hyperparameter tuning to achieve the best model configuration.
- **Provide insights:** Analyze the features that have the most significant impact on used car pricing.

## Machine Learning Techniques Used

The project employs various machine learning techniques, including:
- **Boosting algorithms:** Using models such as Gradient Boosting and XGBoost for their effectiveness in capturing complex relationships in the data.
- **Optuna:** A framework for hyperparameter optimization that uses an efficient search algorithm to find the best parameters for the boosting models.
- **Data preprocessing:** Handling missing values, encoding categorical variables, and scaling numerical features to prepare the data for modeling.
- **Model evaluation:** Assessing performance using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.

## Tools and Libraries

The following tools and libraries are utilized in this project:
- **Pandas:** For data manipulation and preprocessing
- **NumPy:** For numerical computations
- **Scikit-learn:** For model evaluation and data preprocessing utilities
- **XGBoost:** For implementing the eXtreme Gradient Boosting algorithm
- **Optuna:** For hyperparameter tuning to optimize the boosting models
- **Matplotlib/Seaborn:** For visualizing data distributions, feature importance, and model performance

## How to Run the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/PkwyDrv/Data_Projects_TripleTen.git

2. Navigate to the project directory:
   ```bash
   cd Data_Projects_TripleTen/NumericalMethods_UsedCarPricing

3. Install the required dependencies (if not already installed)

1. Open the Jupyter notebook:
   ```bash
   jupyter notebook UsedCarPricePredictBoostingOptuna.ipynb

5. Follow the steps in the notebook to preprocess the data, train the models, perform hyperparameter tuning using Optuna, and evaluate the results.

## Findings
The analysis includes insights such as:

- The effectiveness of different boosting models in predicting used car prices
- Key features that significantly impact the prediction of car prices (e.g., mileage, year, make, and model)
- The optimal hyperparameters found using Optuna for maximizing model accuracy

## Future Work
Potential future enhancements include:

- Experimenting with additional algorithms like CatBoost or LightGBM
- Incorporating more data sources to improve model generalization
- Developing a web application for real-time used car price prediction based on user inputs

## License
This project is open-source and available under the MIT License.

