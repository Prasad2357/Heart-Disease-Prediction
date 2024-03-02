# Heart Disease Classification Prediction

This notebook explores the use of various Python-based machine learning and data science libraries to build a machine learning model for predicting whether or not someone has heart disease based on their medical attributes.

## Dataset
The original data is sourced from the Cleveland dataset available on the [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/Heart+Disease). There is also a version of it available on [Kaggle](kaggle_dataset_link).

## Features
Only 14 attributes are used:
1. (age)
2. (sex)
3. (cp)
4. (trestbps)
5. (chol)
6. (fbs)
7. (restecg)
8. (thalach)
9. (exang)
10. (oldpeak)
11. (slope)
12. (ca)
13. (thal)
14. (num)

## Models

The model is trained using Logistic Regression, KNN, and Random Forest. You can customize the training parameters by modifying the configuration file or using command-line arguments. Refer to the `train.py` script for more details.

## Accuracy

1. Logistic Regression: 0.8852459016393442
2. KNN: 0.6885245901639344
3. Random Forest: 0.8360655737704918

## Visualizations

Explore some visualizations related to the dataset and model performance:

### Correlation Matrix

![correlation_matrix](https://github.com/Prasad2357/Heart-Disease-Prediction/blob/main/Graphs/correlation_matrix.png)

### Feature Selection

![feature_selection](https://github.com/Prasad2357/Heart-Disease-Prediction/blob/main/Graphs/feature_importance.png)

### Scatter plot

![scatter_plot](https://github.com/Prasad2357/Heart-Disease-Prediction/blob/main/Graphs/heart_disease_in_function_of_age_and_max_heart_rate.png)





