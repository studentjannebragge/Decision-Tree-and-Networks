# Decision Tree Practice Project

This project is designed to practice using machine learning algorithms, particularly Decision Trees and the XGBoost classifier. It leverages the Python programming language along with Scikit-Learn and XGBoost libraries.

## Project Overview

In this project, we use Decision Tree and XGBoost models for a classification task on a given dataset. The goal is to build a model capable of predicting the target classes of the test set as accurately as possible. The project involves data preprocessing, model training, and performance evaluation.

## Key Features

- **Decision Tree Classifier**: Used for preliminary modeling of the data.
- **XGBoost Classifier**: A more powerful model that enhances classification accuracy.
- **Performance Metrics**: Uses accuracy measures such as accuracy, confusion matrix, and classification report.

## Installation

The following libraries are required to run the project:

```bash
pip install -r requirements.txt
```

`requirements.txt` includes all libraries used in the project, including:

- pandas
- scikit-learn
- xgboost
- matplotlib

## Project Files

- **tree_trainer.ipynb**: The main notebook containing data processing, model training, and evaluation.
- **README.md**: This file provides an overview of the project.

## Project Steps

1. **Data Loading and Preprocessing**:
   - Data is loaded and preprocessed before training the model.
   - Target classes are encoded numerically using the `LabelEncoder` class.

2. **Model Training**:
   - Decision Tree and XGBoost models are trained using varying amounts of data (`n_data`).

3. **Model Prediction and Evaluation**:
   - Prediction accuracy is calculated using the `accuracy_score` method.
   - The confusion matrix is visualized to assess the results.

4. **Results Visualization and Reporting**:
   - Model accuracy is reported, and the Confusion Matrix is displayed graphically.

## Performance

Metrics used in the project include:

- **Accuracy**: The accuracy of the XGBoost model on the test set.
- **Confusion Matrix**: Visualizes the distribution of predicted and actual classes.

## Additional Information

This project is intended for educational purposes and provides practice in implementing and evaluating machine learning algorithms, particularly Decision Trees and the XGBoost classifier.
