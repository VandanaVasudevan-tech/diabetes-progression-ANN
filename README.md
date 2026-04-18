# diabetes-progression-ANN
A deep learning-based regression model using Artificial Neural Networks (ANN) to predict diabetes progression using the sklearn diabetes dataset, with performance evaluation and model optimization.


# 🧠 Diabetes Progression Prediction using ANN

## 📌 Project Overview

This project focuses on predicting the progression of diabetes using an Artificial Neural Network (ANN). The model is trained on the diabetes dataset from sklearn and aims to analyze how various medical features influence disease progression.

---

## 🎯 Objective

To build, train, and evaluate a deep learning model that predicts diabetes progression and provides insights into key influencing factors.

---

## 📊 Dataset

* Source: `sklearn.datasets.load_diabetes()`
* Features: 10 baseline variables (age, BMI, blood pressure, etc.)
* Target: Quantitative measure of disease progression

---

## ⚙️ Project Workflow

### 1. Data Loading & Preprocessing

* Loaded dataset from sklearn
* Checked for missing values (none found)
* Applied feature normalization using StandardScaler

### 2. Exploratory Data Analysis (EDA)

* Visualized feature distributions
* Generated correlation heatmap
* Identified key influencing features (BMI, BP, etc.)

### 3. ANN Model Building

* Built a Sequential ANN model
* Used ReLU activation in hidden layers
* Output layer for regression prediction

### 4. Model Training

* Split data into training and testing sets
* Used Adam optimizer and Mean Squared Error loss
* Trained model with validation split

### 5. Model Evaluation

* Metrics used:

  * Mean Squared Error (MSE)
  * R² Score

### 6. Model Improvement

* Added additional hidden layer
* Increased number of neurons
* Introduced Dropout for regularization
* Improved overall performance

---

## 📈 Results

| Model Version  | MSE     | R² Score |
| -------------- | ------- | -------- |
| Initial Model  | 5817.13 | -0.0979  |
| Improved Model | 2773.82 | 0.4764   |

### 🔍 Analysis

* Significant reduction in prediction error
* Improved model explains ~48% of variance
* Demonstrates effectiveness of ANN tuning

---

## 🧠 Key Learnings

* Importance of data normalization in ANN
* Impact of architecture tuning on performance
* Role of Dropout in reducing overfitting
* Understanding regression metrics like MSE and R²

---

## 🚀 Future Improvements

* Hyperparameter tuning
* Trying advanced models (XGBoost, Random Forest)
* Cross-validation for better generalization
* Feature engineering

---

## 🛠️ Tech Stack

* Python
* NumPy, Pandas
* Matplotlib, Seaborn
* Scikit-learn
* TensorFlow / Keras

---



## 📌 Conclusion

The ANN model successfully predicts diabetes progression and shows significant improvement after optimization. This project demonstrates the practical application of deep learning in healthcare analytics.

---
