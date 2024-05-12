# AI-ML Assigment

## Overview

This project aims to predict [describe what you're predicting] using machine learning models trained on the provided datasets. We have trained four different models - Random Forest, SARIMAX, LSTM, and GBMRegressor - and compared their performance. The GBMRegressor model yielded the best results.
# Dataset

The dataset consists of two CSV files:

- `Training Dataset.csv`: Contains the training data.
- `Test Dataset.csv`: Contains the test data.

Both datasets have the same structure:

| Column Name      | Description                               |
|------------------|-------------------------------------------|
| ProductType      | Type of the product                       |
| Manufacturer     | Manufacturer of the product               |
| Area Code        | Area code where the product is sourced    |
| Sourcing Channel | Channel through which the product is sourced |
| Product Size     | Size of the product                       |
| Product Type     | Type of the product                       |
| Month of Sourcing| Month when the product is sourced         |
| Sourcing Cost    | Cost of sourcing the product              |

# Models

We trained four models:

- Random Forest
- SARIMAX
- LSTM
- GBMRegressor

# Data Preprocessing

Before training the models, we performed the following preprocessing steps:

- Handled missing values
- Examined and handled outliers in the 'Sourcing Cost' column
- Explored and visualized individual columns
- Engineered features as necessary

# Results

The GBMRegressor model outperformed the other models in terms of [mention the evaluation metric]. Refer to the notebook for detailed results and analysis.

## Overview

This project aims to predict [describe what you're predicting] using machine learning models trained on the provided datasets. We have trained four different models - Random Forest, SARIMAX, LSTM, and GBMRegressor - and compared their performance. The GBMRegressor model yielded the best results.

## Requirements

To run the project, you'll need the following:

- Python 3.x
- Jupyter Notebook
- Required libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - statsmodels
  - lightgbm

You can install the required libraries by running:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn statsmodels lightgbm

# This structure places the workflow details at the top, followed by the detailed explanation and instructions for running the project.
