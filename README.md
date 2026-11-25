# Breast Cancer Prediction Using Machine Learning

A machine learning classification project that uses the Breast Cancer Wisconsin dataset to predict whether a tumour is **malignant or benign** using patient-related numerical features.

This project explores the fundamentals of machine learning, including data preprocessing, classification algorithms, model evaluation and performance comparison using Python and Scikit-learn.

## Project Overview

The objective of this project is to build and evaluate machine learning classification models that identify patterns in tumour measurements and predict the corresponding tumour class.

Two classification algorithms are implemented and compared:

- Logistic Regression
- Random Forest Classifier

The project focuses on understanding how classification models learn from data and how their performance can be evaluated using different metrics.

## Technologies Used

- **Python** – Programming language
- **Jupyter Notebook / Google Colab** – Development environment
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Scikit-learn** – Machine learning algorithms and evaluation metrics

## Dataset

The project uses the built-in Breast Cancer Wisconsin dataset available through `sklearn.datasets`.

The dataset contains numerical features extracted from digitized images of breast mass samples.

The target classes are:

- **Malignant (0):** Cancerous tumour
- **Benign (1):** Non-cancerous tumour

## Project Workflow

1. **Data Loading:** Load the Breast Cancer dataset using Scikit-learn.
2. **Data Exploration:** Examine dataset dimensions, feature names, target distribution and missing values.
3. **Data Preparation:** Separate features and target labels.
4. **Train-Test Split:** Divide the dataset into training and testing sets.
5. **Model Training:** Train Logistic Regression and Random Forest classifiers.
6. **Model Prediction:** Generate predictions using unseen test data.
7. **Model Evaluation:** Evaluate performance using accuracy, precision, recall, F1-score and confusion matrices.
8. **Model Comparison:** Compare both classifiers to understand their performance.

## Evaluation Metrics

The following metrics are used to evaluate the classification models:

| Metric | Purpose |
|---|---|
| Accuracy | Measures overall correct predictions |
| Precision | Measures how many positive predictions were correct |
| Recall | Measures how many actual positive cases were identified |
| F1-score | Balances precision and recall |
| Confusion Matrix | Shows correct and incorrect classifications |

## Key Learnings

Through this project, I gained practical experience with:

- Understanding supervised machine learning.
- Working with classification datasets.
- Exploring and preparing data using Pandas.
- Training Logistic Regression and Random Forest models.
- Understanding train-test splitting.
- Evaluating classification performance.
- Interpreting confusion matrices and classification reports.
- Comparing different machine learning algorithms.

## Future Improvements

- Experiment with additional classification algorithms.
- Apply feature scaling and compare model performance.
- Perform hyperparameter tuning and cross-validation.
- Save the trained model and integrate it with FastAPI.
- Build a prediction API with input validation.

## Disclaimer

This project is developed for educational purposes to explore machine learning classification techniques. It is not intended for medical diagnosis or clinical decision-making. The predictions should not be used as a substitute for professional medical advice.

## Author

**Madiha Shaikh**
