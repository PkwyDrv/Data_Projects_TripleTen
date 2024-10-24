# Predicting Gold Recovery from Ore Using sMAPE

This project focuses on predicting the recovery rate of gold from ore processing using machine learning regression techniques. The goal is to build a model that can accurately forecast gold recovery efficiency, which is crucial for optimizing the mineral processing operations.

## Project Overview

The Jupyter notebook demonstrates the process of building a regression model to predict gold recovery rates from ore, including:
- Data preprocessing and feature engineering
- Training different regression models
- Evaluating model performance using symmetric Mean Absolute Percentage Error (sMAPE)
- Analyzing the results to improve prediction accuracy

## Dataset

The dataset contains information about ore processing, including:
- Features related to different stages of the mineral processing (e.g., flotation, cleaning, final output)
- Various parameters measured during the processing (e.g., reagent levels, particle size distribution)
- Target variable: actual recovery of gold

The dataset is used to train machine learning models that predict gold recovery rates based on input features.

## Key Objectives

- **Predict gold recovery rates:** Develop a regression model to estimate the recovery rate of gold based on processing parameters.
- **Optimize prediction accuracy:** Use symmetric Mean Absolute Percentage Error (sMAPE) as the evaluation metric to gauge model performance.
- **Identify key factors influencing recovery:** Analyze which processing parameters have the most significant impact on the predicted recovery rates.

## Machine Learning Techniques Used

The project employs several machine learning techniques for regression analysis, such as:
- **Linear Regression:** For a baseline predictive model
- **Random Forest Regression:** To capture non-linear relationships in the data
- **Gradient Boosting Regression:** For more accurate predictions using ensemble methods
- **Data preprocessing:** Handling missing values, scaling features, and engineering new features
- **Model evaluation:** Using sMAPE as the main metric to assess prediction accuracy

## Tools and Libraries

The following tools and libraries are used in this project:
- **Pandas:** For data manipulation and preprocessing
- **Scikit-learn:** For implementing machine learning models and evaluation techniques
- **NumPy:** For numerical computations
- **Matplotlib/Seaborn:** For visualizing data distributions and model performance

## Symmetric Mean Absolute Percentage Error (sMAPE)

The main evaluation metric used in this project is symmetric Mean Absolute Percentage Error (sMAPE), which is calculated as:
\[
\text{sMAPE} = \frac{1}{N} \sum_{i=1}^{N} \frac{|y_i - \hat{y}_i|}{(|y_i| + |\hat{y}_i|) / 2} \times 100\%
\]
where \(y_i\) is the actual value, \(\hat{y}_i\) is the predicted value, and \(N\) is the number of observations.

sMAPE is suitable for this task because it provides a percentage-based error that accounts for both overestimation and underestimation.

## How to Run the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/PkwyDrv/Data_Projects_TripleTen.git

2. Navigate to the project directory:
   ```bash
   cd Data_Projects_TripleTen/GoldOre_sMAPE
   
3. Install the necessary dependencies (if not already installed)

4. Open the Jupyter notebook:
   ```bash
   git clone https://github.com/PkwyDrv/Data_Projects_TripleTen.git

5. Follow the steps in the notebook to preprocess the data, train models, and evaluate the results using sMAPE.

## Findings
The analysis provides insights into:

- The effectiveness of different regression models in predicting gold recovery rates
- Key features influencing the prediction of gold recovery
- The most suitable model for minimizing sMAPE and providing accurate forecasts

## Future Work
Possible future directions for this project include:

- Incorporating more advanced regression techniques, such as XGBoost or LightGBM
- Using feature selection techniques to reduce dimensionality and improve model performance
- Exploring time-series modeling if the dataset contains temporal information

## License
This project is open-source and available under the MIT License.
