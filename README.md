# 🌸 Iris Flower Classification using KNN

This project uses the **K-Nearest Neighbors (KNN)** machine learning algorithm to classify Iris flowers into different species based on their measurements.

## 📌 Project Overview

The model predicts the species of an Iris flower using four features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The target variable is the **Iris Species**.

## 📊 Dataset

The dataset contains **150 rows and 5 columns**.

### Features:
- sepal_length
- sepal_width
- petal_length
- petal_width

### Target:
- `species`

The dataset contains three Iris species:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

## 🤖 Machine Learning Algorithm

**K-Nearest Neighbors (KNN)** is used for classification.

Steps performed in the project:

1. Load the Iris dataset
2. Check the dataset
3. Check missing values
4. Separate features (X) and target (y)
5. Split data into training and testing sets
6. Apply StandardScaler for feature scaling
7. Train the KNN classifier
8. Predict the Iris species
9. Calculate model accuracy

## 📈 Model Performance

The KNN model achieved an accuracy of approximately **100% (1.0)** on the test dataset.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## 📁 Project Files

```text
Iris-KNN-Model/
│
├── Iris_Data.csv
├── knn.ipynb
└── README.md
