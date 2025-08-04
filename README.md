# Car_Price_Prediction
---

# 🚗 Car Price Prediction - ML Project

This project predicts the selling price of a car based on various features using Machine Learning techniques. It is designed as a supervised regression problem and uses Python with libraries like Pandas, Scikit-Learn, and Matplotlib for data handling, training, and visualization.

## 📁 Project Structure

```
CarPricePrediction/
├── CarPricePrediction.ipynb  # Main Jupyter notebook
├── data/                     # (Optional) Dataset directory
├── README.md                 # Project overview
└── requirements.txt          # Python dependencies
```

## 🔍 Problem Statement

Given a dataset containing information about used cars, the goal is to develop a model that accurately predicts the **selling price** of a car using features such as:

* Selling Price
* Year of Manufacture
* Kilometers Driven
* Fuel Type
* Seller Type
* Transmission
* Owner

## 📊 Dataset

The dataset includes:

* Numerical and categorical features
* Target: `Selling_Price`

The data was preprocessed by:

* Handling categorical values (e.g., encoding fuel and transmission types)
* Calculating car age from manufacturing year
* Removing outliers and checking feature correlations

## 🧠 ML Algorithms Used

* Linear Regression

The models are evaluated using:
* R² Score
* MAE (Mean Absolute Error)
* Cross-validation

## 🛠️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/Akshu121796/CarPricePrediction.git
cd CarPricePrediction
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the Jupyter Notebook:

```bash
jupyter notebook CarPricePrediction.ipynb
```

## 📈 Results

* Best performing model: **Linear Regression**
* R² Score: \~0.91
* Trained model can generalize well on unseen test data

## ✅ Features Implemented

* Data Cleaning and Feature Engineering
* Model Training and Comparison
* Residual Plots and Error Analysis
* Model Serialization using `pickle`


## 📦 Requirements

* Python 3.7+
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* jupyter

(Include in `requirements.txt`)

---------
