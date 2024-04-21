# Business Analytics Project: Bank Customer Churn Model

This repository contains a Jupyter Notebook that demonstrates the building of a customer churn prediction model for Akhya Bank using the Support Vector Machine (SVM) algorithm. The model aims to identify customers who are likely to leave the bank, allowing the bank to take proactive measures to retain them.

## Overview
This repository focuses on predicting bank customer churn, a critical metric for banking institutions. By leveraging data analytics techniques, we aim to build a predictive model that identifies customers at risk of churning.

## Objective
Developing a robust predictive model to accurately identify bank customers likely to churn, enabling proactive measures to retain valuable customers and enhance profitability.

## Key Features
- **Data Exploration**: Understanding dataset characteristics and churn patterns.
- **Feature Engineering**: Identifying and creating relevant features for churn prediction.
- **Model Development**: Utilizing machine learning algorithms to build predictive models.
- **Model Evaluation**: Rigorously assessing model performance for reliability.
- **Insights and Recommendations**: Extracting actionable insights to mitigate churn risk.

## Dataset

The dataset used in this project is titled "Bank Churn Modelling.csv" and is available at the following link: [https://github.com/YBI-Foundation/Dataset/raw/main/Bank%20Churn%20Modelling.csv](https://github.com/YBI-Foundation/Dataset/raw/main/Bank%20Churn%20Modelling.csv)

The dataset contains the following features:

- `RowNumber`: Row number
- `CustomerId`: Customer ID
- `Surname`: Surname of the customer
- `CreditScore`: Credit score of the customer
- `Geography`: Country where the customer resides
- `Gender`: Gender of the customer
- `Age`: Age of the customer
- `Tenure`: Number of years the customer has been with the bank
- `Balance`: Account balance of the customer
- `NumOfProducts`: Number of bank products the customer has subscribed to
- `HasCrCard`: Whether the customer has a credit card or not
- `IsActiveMember`: Whether the customer is an active member or not
- `EstimatedSalary`: Estimated salary of the customer
- `Exited`: Whether the customer has left the bank or not (target variable)

## Approach

The notebook follows these steps:

1. Import necessary libraries
2. Load the dataset
3. Perform exploratory data analysis
4. Preprocess the data (handle missing values, encode categorical variables, etc.)
5. Split the data into training and testing sets
6. Apply random undersampling and oversampling techniques to handle class imbalance
7. Standardize the features
8. Train an SVM model on the original and resampled data
9. Evaluate the model performance using various metrics
10. Perform hyperparameter tuning using GridSearchCV
11. Compare the performance of different models

## Requirements

To run the notebook, you'll need the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn

You can install these libraries using pip:

```
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

## Usage

1. Clone this repository to your local machine.
2. Open the `Akhya_Bank_Customer_Churn_Model.ipynb` notebook in Jupyter Notebook or Google Colab.
3. Follow the instructions in the notebook to execute the code and build the customer churn prediction model.

## Contributing

If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.
