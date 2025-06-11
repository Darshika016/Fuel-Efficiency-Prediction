# 🚗 Predicting Fuel Efficiency using TensorFlow

## 🔍 Overview
This project aims to build a regression model using **TensorFlow** to predict the fuel efficiency (measured in miles per gallon - MPG) of cars based on various attributes such as horsepower, cylinders, displacement, and weight.

---

## 🎯 Objective
To use a deep learning model for predicting fuel efficiency from automobile specifications using a real-world dataset. This demonstrates regression using TensorFlow's high-level Keras API.

---

## 🛠️ Tech Stack / Tools Used
- **Python**
- **TensorFlow / Keras**
- **Pandas**
- **Matplotlib & Seaborn** (for visualization)
- **Scikit-learn** (for preprocessing and metrics)
- **Jupyter Notebook / Google Colab**

---

## 📄 Dataset Description
The dataset used is the [Auto MPG dataset](https://archive.ics.uci.edu/ml/datasets/auto+mpg), containing details like:
- Cylinders  
- Displacement  
- Horsepower  
- Weight  
- Acceleration  
- Model Year  
- Origin  
- MPG (target)

---

## ⚙️ Features
- Data preprocessing (handling missing values, normalization)
- Encoding categorical variables
- Splitting into training/testing sets
- Building and training a neural network with TensorFlow
- Evaluating the model on test data
- Visualizing loss and prediction performance

---

## 📂 Folder Structure
```
Fuel-Efficiency-Prediction/
├── fuel_efficiency_model.ipynb
├── auto_mpg.csv
├── requirements.txt
└── README.md
```

---

## ▶️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/Darshika016/fuel-efficiency-prediction.git
cd fuel-efficiency-prediction
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the notebook
Use Jupyter Notebook or Colab to run:
```
jupyter notebook fuel_efficiency_model.ipynb

```

---

## 📊 Sample Output
- Training & validation loss curves
- Predicted MPG vs Actual MPG scatter plot
- Model performance metrics like MAE & MSE

  ---

## ✅ Conclusion
This project shows how to apply deep learning for regression tasks using TensorFlow. It covers the full machine learning pipeline — from data preprocessing to model evaluation — and highlights your skills in building neural networks for real-world problems.
