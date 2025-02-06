# Bank Customer Churn Prediction Dashboard

This repository contains the code and resources for a **Bank Customer Churn Prediction Dashboard**. The dashboard is designed to analyze and predict customer churn based on a dataset containing various customer attributes such as credit score, age, balance, tenure, and more. The goal is to help banks identify customers who are likely to churn and take proactive measures to retain them.

## Table of Contents
1. [Dataset Overview](#dataset-overview)
2. [Preprocessing](#preprocessing)
3. [Dashboard Features](#dashboard-features)
4. [How to Use](#how-to-use)
5. [Contributing](#contributing)

---

## Dataset Overview

The dataset used in this project is named `Bank Customer Churn Prediction.csv`. It contains the following columns:

- **customer_id**: Unique identifier for each customer.
- **credit_score**: Credit score of the customer.
- **country**: Country of residence (e.g., France, Spain, Germany).
- **gender**: Gender of the customer (Male/Female).
- **age**: Age of the customer.
- **tenure**: Number of years the customer has been with the bank.
- **balance**: Account balance of the customer.
- **products_number**: Number of bank products the customer uses.
- **credit_card**: Whether the customer has a credit card (1 = Yes, 0 = No).
- **active_member**: Whether the customer is an active member (1 = Yes, 0 = No).
- **estimated_salary**: Estimated salary of the customer.
- **churn**: Whether the customer has churned (1 = Yes, 0 = No).

The dataset contains 10,000 rows, each representing a unique customer.

---

## Preprocessing

During the preprocessing phase, the following steps were taken to prepare the data for analysis and modeling:

1. **Categorization of Columns**:
   - **Credit Score**: The `credit_score` column was categorized into separate bins (e.g., Low, Medium, High) to better analyze its impact on churn.
   - **Balance**: The `balance` column was also categorized into bins (e.g., Low, Medium, High) to simplify analysis and visualization.
   - **Age**: The `age` column was grouped into age ranges (e.g., 18-30, 31-45, 46-60, 60+) to make it easier to analyze trends across different age groups.

2. **Removal of Estimated Salary**:
   - The `estimated_salary` column was removed from the dataset. This decision was made to focus on other key factors that may have a more direct impact on churn, such as balance and credit score.

3. **Data Cleaning**:
   - Any missing or inconsistent data was handled appropriately to ensure the dataset was clean and ready for analysis.

---

## Dashboard Features

The dashboard provides the following features:

1. **Interactive Visualizations**: The dashboard includes interactive charts and graphs to visualize key metrics such as churn rate, customer demographics, and more.
2. **Filtering Options**: Users can filter data by country, gender, age group, and other attributes to get a more detailed view.
3. **Key Metrics**: The dashboard displays key metrics such as the total number of customers, churn rate, and average balance.
4. **Export Options**: Users can export the data and visualizations for further analysis.

---

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/YahiaAldeeb/BankChurnAnalysis.git
   cd BankChurnAnalysis


## Contributing
Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes.
4. Push your branch and submit a pull request.

Please ensure your code follows the project's coding standards and includes appropriate documentation.

## Acknowledgments

1. The dataset used in this project is sourced from Kaggle.
2. Special thanks to the open-source community for providing the tools and libraries used in this project.

