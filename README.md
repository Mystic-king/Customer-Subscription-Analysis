# Customer Subscription Analysis

This repository contains a Python-based analysis project that focuses on understanding customer behavior based on subscription data. The project includes data analysis, visualization, and a machine learning model to predict customer churn.

## Table of Contents

- [Overview](#overview)
- [Data Description](#data-description)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis Steps](#analysis-steps)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Customer Subscription Analysis project aims to analyze customer subscription data to extract meaningful insights. The project covers the following:

- Analyzing the distribution of subscription types, monthly revenue, and demographic factors such as age and gender.
- Visualizing the data with interactive plots.
- Predicting customer churn using a machine learning model.

## Data Description

The dataset contains the following columns:

- **User ID**: Unique identifier for each user.
- **Subscription Type**: The type of subscription (e.g., Free, Basic, Premium).
- **Monthly Revenue**: The revenue generated from the user each month.
- **Join Date**: The date the user joined the service.
- **Last Payment Date**: The last date the user made a payment.
- **Country**: The user's country.
- **Age**: The age of the user.
- **Gender**: The gender of the user.
- **Device**: The device used by the user (e.g., Mobile, Desktop).
- **Plan Duration**: Duration of the subscription plan (in months).

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/customer-subscription-analysis.git
    cd customer-subscription-analysis
    ```

2. **Create a virtual environment**:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the analysis:

1. **Run the Jupyter Notebook**:
    ```bash
    jupyter notebook Customer_Subscription_Analysis.ipynb
    ```

2. **Follow the steps in the notebook** to load the data, perform analysis, visualize the results, and train the machine learning model.

## Analysis Steps

The project is divided into several key steps:

1. **Data Cleaning**:
   - Handle missing values.
   - Convert data types where necessary.

2. **Exploratory Data Analysis (EDA)**:
   - Analyze the distribution of subscription types, monthly revenue, age, gender, and more.
   - Visualize data with interactive plots using Plotly.

3. **Feature Engineering**:
   - Create new features like `Payment Month` and `Churn`.
   - Encode categorical variables.

4. **Machine Learning Model**:
   - Train a Random Forest model to predict customer churn.
   - Evaluate the model using accuracy, precision, and recall.

## Results

- **Subscription Type Distribution**:
  - Visualizations show the proportion of each subscription type.
  
- **Monthly Revenue Trends**:
  - Insights into revenue trends over time.

- **Churn Prediction**:
  - The model predicts customer churn with an accuracy of `X%`.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
