#  Diabetes Prediction using K-Nearest Neighbors (KNN)

##  Overview

This project implements a **K-Nearest Neighbors (KNN)** classification model to predict whether a patient is likely to have diabetes based on medical diagnostic measurements.

The project includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, hyperparameter analysis, and prediction using user-provided input.

---

##Problem Statement

Early detection of diabetes can help patients receive timely treatment and reduce the risk of serious health complications. This project aims to build a machine learning model that predicts diabetes using patient health data.

---

##  Dataset

The project uses the **Pima Indians Diabetes Dataset**, which contains medical information collected from female patients.

### Features

| Feature | Description |
|----------|-------------|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure |
| SkinThickness | Triceps skin fold thickness |
| Insulin | 2-Hour serum insulin |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes pedigree function |
| Age | Patient age |

### Target Variable

- **0** → Non-Diabetic
- **1** → Diabetic

---

##  Technologies Used

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Exploratory Data Analysis (EDA)

The following visualizations were performed:

- Outcome Distribution
- Glucose vs BMI Scatter Plot

These visualizations help understand the distribution of the dataset and relationships between important medical features.

---

##  Machine Learning Workflow

1. Load the dataset
2. Explore the dataset
3. Perform data preprocessing
4. Split the data into training and testing sets
5. Standardize features using `StandardScaler`
6. Train the K-Nearest Neighbors classifier
7. Predict on test data
8. Evaluate model performance
9. Find the optimal value of **K**
10. Predict diabetes using user input

---

##  Model Performance

### Accuracy

**68.83%**

### Classification Report

| Metric | Class 0 | Class 1 |
|---------|---------|---------|
| Precision | 0.73 | 0.58 |
| Recall | 0.81 | 0.47 |
| F1-Score | 0.77 | 0.52 |

### Confusion Matrix

```
[[80 19]
 [29 26]]
```

---

## Hyperparameter Tuning

The model was evaluated using multiple values of **K (1–20)**.

A graph of **Accuracy vs K Value** was plotted to observe how the choice of K influences model performance.

---

## Features

- Exploratory Data Analysis
- Data Visualization
- Feature Scaling
- KNN Classification
- Accuracy Evaluation
- Classification Report
- Confusion Matrix
- Hyperparameter Analysis
- User Input Prediction

---

## 📁 Project Structure

```
KNN-Project/
│
├── KNNAlgorithm.ipynb
├── diabetess.csv
├── README.md
```

---

## Installation

Install the required libraries:

```bash
pip install pandas matplotlib scikit-learn
```
Launch Jupyter Notebook:

```bash
jupyter notebook
```
Open:

```
KNNAlgorithm.ipynb
```
Run all notebook cells.

---

##  Project Outputs

The notebook generates the following outputs:

- Outcome Distribution Chart
- Glucose vs BMI Scatter Plot
- Classification Report
- Confusion Matrix
- Accuracy vs K Value Plot
- Diabetes Prediction using User Input

---

## 🔮 Future Improvements

- Improve model accuracy through hyperparameter tuning
- Compare KNN with Logistic Regression, Decision Tree, and Random Forest
- Handle missing or zero values more effectively
- Build a Streamlit web application for real-time predictions
- Deploy the model on the cloud

---

## Key Learning Outcomes

Through this project, I learned:

- Data preprocessing techniques
- Exploratory Data Analysis (EDA)
- Feature scaling using StandardScaler
- K-Nearest Neighbors (KNN) algorithm
- Model evaluation using accuracy, precision, recall, and F1-score
- Hyperparameter tuning
- Building an end-to-end machine learning workflow





Aspiring Software Engineer | Machine Learning Enthusiast

GitHub: https://github.com/YOUR_GITHUB_USERNAME
