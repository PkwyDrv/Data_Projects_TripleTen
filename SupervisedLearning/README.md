# Bank Customer Retention Analysis Using Supervised Learning

This project focuses on predicting customer retention for a bank using supervised learning techniques. The analysis aims to identify customers who are likely to churn and understand the factors influencing their decision, helping the bank to take proactive measures to improve customer retention.

## Project Overview

The Jupyter notebook covers the complete workflow of building a machine learning model to predict customer churn, including:
- Data cleaning and preprocessing
- Feature engineering and selection
- Training and evaluating supervised learning models
- Interpreting the results to gain insights into customer retention

## Dataset

The dataset contains information about bank customers, including:
- Customer demographics (e.g., age, gender, geographic location)
- Account information (e.g., balance, tenure, number of products)
- Behavioral data (e.g., activity level, credit score)
- Churn label indicating whether the customer left the bank

This data is used to train machine learning models to predict the likelihood of churn.

## Key Objectives

- **Predict customer churn:** Build and train machine learning models to identify customers who are at risk of leaving the bank.
- **Understand churn drivers:** Analyze the key features that contribute to customer churn and retention.
- **Improve retention strategies:** Provide actionable insights to help the bank reduce churn and enhance customer satisfaction.

## Machine Learning Techniques Used

The project utilizes various supervised learning techniques, such as:
- **Logistic Regression:** For baseline classification performance
- **Decision Trees and Random Forest:** To capture non-linear relationships in the data
- **Gradient Boosting:** For more accurate predictions using ensemble methods
- **Hyperparameter tuning:** Applying Grid Search and Random Search to optimize model performance
- **Evaluation metrics:** Using metrics like accuracy, precision, recall, ROC-AUC, and F1-score to assess model effectiveness

## Tools and Libraries

The following tools and libraries are used:
- **Pandas:** For data manipulation and analysis
- **Scikit-learn:** For machine learning algorithms, model evaluation, and hyperparameter tuning
- **Matplotlib/Seaborn:** For visualizing data distributions and model performance
- **NumPy:** For numerical computations

## How to Run the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/PkwyDrv/Data_Projects_TripleTen.git

2. Navigate to the project directory:
   ```bash
   cd Data_Projects_TripleTen/SupervisedLearning

3. Install the required dependencies (if not already installed)

4. Open the Jupyter notebook:
   ```bash
   jupyter notebook SupervisedLearningBankCustomerRetension.ipynb

5. Follow the steps in the notebook to preprocess the data, train models, and evaluate results.

## Findings
The notebook provides insights on:

- Key factors contributing to customer churn (e.g., credit score, account balance)
- Comparison of different machine learning models for predicting churn
- Recommended strategies for improving customer retention based on the analysis
  
## Future Work
Potential future enhancements include:

- Incorporating additional customer data for better model accuracy
- Applying deep learning techniques to improve prediction performance
- Developing a real-time churn prediction system

License
This project is open-source and available under the MIT License.
