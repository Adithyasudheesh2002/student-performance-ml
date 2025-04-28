# Student Performance Prediction

This project uses machine learning to predict student academic performance. It employs several classification and regression algorithms such as **Logistic Regression**, **Decision Tree Classifier**, **Random Forest Classifier**, and **Linear Regression** to predict student success based on academic features.

## Project Overview

The main goal of this project is to predict the academic performance of students based on various features like study time, family background, and previous grades. The dataset has been preprocessed to handle missing values, encode categorical variables, and scale features.

## Key Features

- **Data Preprocessing:** 
  - Handled missing data.
  - Encoded categorical variables.
  - Improved data quality by 33% to enhance model performance.
  
- **Modeling:**
  - Implemented **classification algorithms**: Logistic Regression, Decision Tree Classifier, and Random Forest Classifier.
  - Implemented **regression algorithms**: Linear Regression, Decision Tree Regressor, and Random Forest Regressor.
  
- **Evaluation Metrics:**
  - **Accuracy**, **Precision**, **Recall**, **F1-Score** for classification models.
  - **R² Score**, **RMSE** for regression models.

## Results

### Classification:
- **Logistic Regression**: Accuracy: 92.41%
- **Decision Tree Classifier**: Accuracy: 88.61%
- **Random Forest Classifier**: Accuracy: 91.14%

### Regression:
- **Linear Regression**: R² Score: 0.72, RMSE: 2.38
- **Decision Tree Regressor**: R² Score: 0.66, RMSE: 2.62
- **Random Forest Regressor**: R² Score: 0.81, RMSE: 1.98

## Requirements

- **Python 3.x**
- **Libraries**: 
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `sklearn`

## How to Run

1. Open the [Google Colab Notebook](https://colab.research.google.com/drive/1QJKJyubmb3iC7-pi5fpedmUSjD45IcNU?usp=sharing)
2. Run the notebook from top to bottom.
3. Follow the instructions in the notebook to load the dataset, preprocess the data, train the models, and evaluate the results.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
