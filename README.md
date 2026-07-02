# JUPYTERLAB-INSAURANCE-
Predictive ML regression model that estimates individual health insurance costs using Python and Scikit-Learn. Preprocessed demographic data and achieved a strong 79.34% R² test accuracy.
# 🏥 Insurance Cost Prediction using Machine Learning

## 📌 Project Overview

This project is a Machine Learning regression model that predicts the estimated medical insurance cost (premium/charges) for an individual based on various personal attributes such as age, BMI, number of children, smoking status, gender, and region.

The objective of this project is to demonstrate the complete machine learning workflow—from data preprocessing and model training to model evaluation and prediction.

---

## 🚀 Features

- Predicts insurance costs for individuals
- Data preprocessing and feature encoding
- Train-test data splitting
- Linear Regression model implementation
- Model performance evaluation using R² Score
- Clean and easy-to-understand implementation

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## 📂 Project Structure

```
Insurance-Cost-Prediction/
│
├── Insurance_Cost_Prediction.ipynb
├── insurance.csv
├── README.md
└── requirements.txt
```

---

## 📊 Machine Learning Workflow

### 1. Data Collection

The insurance dataset contains information such as:

- Age
- Gender
- BMI
- Number of Children
- Smoking Status
- Region
- Insurance Charges (Target Variable)

---

### 2. Data Preprocessing

The dataset was cleaned and prepared before training the model by:

- Checking for missing values
- Encoding categorical variables
- Separating features and target variable
- Preparing data for model training

---

### 3. Train-Test Split

The dataset was divided into training and testing sets using:

```python
from sklearn.model_selection import train_test_split
```

This ensures that the model is trained on one portion of the data and evaluated on unseen data to measure its real-world performance.

---

### 4. Model Building

A Linear Regression model was used for prediction.

```python
from sklearn.linear_model import LinearRegression
```

Linear Regression is a supervised machine learning algorithm used for predicting continuous numerical values by establishing a linear relationship between input features and the target variable.

---

### 5. Model Evaluation

The model performance was evaluated using the **R² Score**.

```python
from sklearn.metrics import r2_score
```

The R² Score measures how well the model explains the variance in the target variable.

- **R² Score = 1**
  - Perfect prediction

- **R² Score = 0**
  - Model performs no better than predicting the average value

- **R² Score < 0**
  - Poor model performance

---

## 📈 Model Performance

**Test R² Score**

```
0.7934410193492923
```

### Interpretation

The model achieves an **R² Score of approximately 0.793**, which means it explains about **79.34% of the variation** in insurance charges using the available features.

This indicates that the Linear Regression model provides a good fit for the dataset while still leaving room for improvement using more advanced regression algorithms.

---

## 📦 Libraries Used

```python
import pandas as pd
import numpy as np

from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import r2_score
```

---

## ▶️ How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/your-username/Insurance-Cost-Prediction.git
```

2. Navigate to the project directory

```bash
cd Insurance-Cost-Prediction
```

3. Install the required libraries

```bash
pip install -r requirements.txt
```

4. Open the Jupyter Notebook

```bash
jupyter notebook
```

5. Run all cells to train the model and generate predictions.

---

## 🎯 Future Improvements

- Improve prediction accuracy using advanced regression algorithms such as:
  - Random Forest Regressor
  - XGBoost Regressor
  - Gradient Boosting Regressor
- Perform hyperparameter tuning
- Deploy the model using Flask or Streamlit
- Create an interactive web application

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Data preprocessing
- Feature engineering
- Machine Learning Regression
- Model evaluation
- Scikit-learn
- Git & GitHub version control

---

## 🤝 Contributing

Contributions, suggestions, and feedback are always welcome.

Feel free to fork the repository and create a pull request.

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!

---
