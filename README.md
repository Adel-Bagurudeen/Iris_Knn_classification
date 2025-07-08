# Iris Flower Classification with K-Nearest Neighbors (KNN)

This project demonstrates a machine learning application using the **Iris flower dataset** to classify Iris species based on their morphological features. The classification is performed using the **K-Nearest Neighbors (KNN)** algorithm.

## Project Objective

The objective is to accurately classify Iris flowers into one of three species (*Setosa*, *Versicolor*, *Virginica*) based on the following features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Dataset Overview

- **Source**: Iris dataset from `sklearn.datasets`
- **Composition**: 150 samples, 3 classes (species), 4 features

## Tools and Libraries

- **Programming Language**: Python
- **Environment**: Google Colab or Jupyter Notebook
- **Libraries**:
  - `pandas` (data manipulation)
  - `scikit-learn` (machine learning)
  - `matplotlib` (visualization, optional)
  - `seaborn` (exploratory data analysis, optional)

## Algorithm

- **K-Nearest Neighbors (KNN)** 
- **Default Configuration**: k = 3, with potential for hyperparameter tuning to optimize performance

## Methodology

1. Load the Iris dataset from `sklearn.datasets`
2. Transform the dataset into a `pandas.DataFrame` for ease of handling
3. Conduct exploratory data analysis (optional, for insights into data distribution)
4. Split the dataset into **training** and **testing** subsets
5. Implement the **KNN Classifier**
6. Train the model and generate predictions
7. Assess model performance using the **accuracy score**
8. Compare actual versus predicted classifications

## Performance Metrics

The model achieved an accuracy exceeding **95%** on the test set with **k = 3**.

## Sample Output
https://github.com/user-attachments/assets/a35a22da-29d8-4f3a-a3db-60438fab4be1
