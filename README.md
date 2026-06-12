# Wine Quality Classification

## Overview

This project focuses on predicting wine quality using machine learning techniques. A Random Forest Classifier was trained on physicochemical properties of wine to classify wines into their respective quality categories.

The objective of the project is to understand the complete machine learning workflow, including data preprocessing, model training, evaluation, and performance analysis.

## Dataset

The project uses the WineQT dataset obtained from Kaggle.

The dataset contains several physicochemical properties of wine, including:

* Fixed Acidity
* Volatile Acidity
* Citric Acid
* Residual Sugar
* Chlorides
* Free Sulfur Dioxide
* Total Sulfur Dioxide
* Density
* pH
* Sulphates
* Alcohol

Target Variable:

* Quality

## Data Preprocessing

The following preprocessing steps were performed:

* Loaded the dataset using Pandas
* Checked for missing values
* Removed the Id column as it does not contribute to prediction
* Separated features and target variable
* Split the dataset into training and testing sets

## Model

Algorithm Used:

Random Forest Classifier

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction performance and reduce overfitting.

## Model Evaluation

The model was evaluated using:

* Accuracy Score
* Confusion Matrix
* Confusion Matrix Visualization

### Results

Accuracy Achieved: 71.62%

Number of Classes: 6

The model was able to classify wine quality across six quality categories present in the dataset.

## Technologies Used

* Python
* Pandas
* Scikit Learn
* Matplotlib

## Project Structure

```text
wine-quality-classification/

├── Wine_Quality_Classification.ipynb
├── WineQT.csv
├── README.md
└── requirements.txt
```

## How to Run

1. Clone the repository

2. Install the required libraries

3. Open the notebook or Python file

4. Run all cells to train and evaluate the model

## Learning Outcomes

Through this project, the following concepts were applied:

* Data preprocessing
* Feature selection
* Train test split
* Random Forest Classification
* Model evaluation
* Confusion Matrix analysis

