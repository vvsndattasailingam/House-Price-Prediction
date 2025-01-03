# House Price Prediction

## Overview

This project is part of the **Large Scale Data Processing** coursework and focuses on predicting house prices based on various attributes such as location, house type, area, and more. It leverages regression techniques to provide accurate predictions using machine learning.

## Features

1. Data preprocessing with handling missing values, outliers, and feature transformations.
2. Exploratory Data Analysis (EDA) with visualizations for better data understanding.
3. Multiple regression models: Linear Regression, Ridge Regression, Lasso Regression, and Elastic Net.
4. Evaluation metrics like RMSE, MAE, and R-squared for model comparison.
5. Integration with Hadoop for large-scale data handling.

## Prerequisites

- Python 3.7 or later
- Required libraries (see `requirements.txt`)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/vvsndattasailingam/House-Price-Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd House-Price-Prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Place the `train.csv` and `test.csv` datasets in the project directory.
2. Open the Jupyter notebook `House price prediction.ipynb` and run the cells sequentially.
3. Review the visualizations, model performance metrics, and predictions.

## Dataset

The dataset is sourced from [Kaggle's House Price Prediction Challenge](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data).

## Results

The project compares multiple regression models to determine the most effective technique for predicting house prices.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Acknowledgements

- Python libraries: pandas, NumPy, scikit-learn, matplotlib, seaborn.
- Kaggle for providing the dataset.
