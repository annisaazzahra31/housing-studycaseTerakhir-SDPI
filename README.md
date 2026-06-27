# 🏠 House Price Prediction for First-Time Home Buyers

Machine Learning project to analyze the factors affecting house prices and predict property values using regression models. This project aims to help **first-time home buyers** make more informed purchasing decisions through data-driven price estimation.

---

## 📖 Overview

Buying a house is one of the biggest financial decisions for many people, especially first-time home buyers. However, property prices are influenced by many factors such as:

- Property area
- Number of bedrooms
- Number of bathrooms
- Stories
- Parking capacity
- Furnishing status
- Main road access
- Preferred location
- Additional facilities

Without sufficient market knowledge, buyers often struggle to determine whether a property's asking price is reasonable.

This project analyzes these factors and develops predictive models that estimate house prices based on property characteristics.

---

## 🎯 Objectives

- Analyze the characteristics that influence house prices.
- Explore patterns within the housing dataset.
- Build predictive machine learning models.
- Compare multiple regression algorithms.
- Evaluate model performance using regression metrics.
- Provide objective price estimation to support purchasing decisions.

---

## 📊 Dataset

**Dataset:** Housing Prices Dataset

The dataset consists of:

- **545 observations**
- **13 attributes**

### Target Variable

- `price`

### Numerical Features

- area
- bedrooms
- bathrooms
- stories
- parking

### Categorical Features

- mainroad
- guestroom
- basement
- hotwaterheating
- airconditioning
- prefarea
- furnishingstatus

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔄 Project Workflow

```text
Dataset
      │
      ▼
Data Understanding
      │
      ▼
Exploratory Data Analysis (EDA)
      │
      ▼
Data Cleaning
      │
      ▼
Feature Encoding
      │
      ▼
Train-Test Split
      │
      ▼
Model Training
 ├── Linear Regression
 ├── Ridge Regression
 └── Lasso Regression
      │
      ▼
Model Evaluation
      │
      ▼
Business Insights
```

---

## 📈 Exploratory Data Analysis

The EDA includes:

- Dataset overview
- Statistical summary
- Missing value analysis
- Duplicate checking
- House price distribution
- Relationship between area and price
- Effect of bedrooms and bathrooms
- Preferred area analysis
- Furnishing status analysis
- Correlation heatmap
- Business insights

---

## 🤖 Machine Learning Models

Three regression algorithms are implemented:

### Linear Regression
Baseline regression model for predicting house prices.

### Ridge Regression
Linear regression with L2 Regularization to reduce overfitting.

### Lasso Regression
Linear regression with L1 Regularization that also performs feature selection.

---

## 📏 Evaluation Metrics

The models are evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 📂 Project Structure

```
.
├── Housing.csv
├── STUDY_CASE_TERAKHIR_SDPI.ipynb
├── README.md
└── images/
```

---

## 🚀 Getting Started

### Clone Repository

```bash
git clone https://github.com/yourusername/house-price-prediction.git
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run Notebook

```bash
jupyter notebook
```

Open:

```
STUDY_CASE_TERAKHIR_SDPI.ipynb
```

---

## 💼 Business Value

This project provides benefits for first-time home buyers by:

- Understanding which property characteristics most influence prices.
- Comparing properties objectively.
- Estimating fair market prices.
- Reducing the risk of purchasing overpriced properties.
- Supporting more confident and data-driven purchasing decisions.

---

## 👥 Team

**Group 7**

- Annisa Azzahra Rahmah
- Eliezer Sharon Hutabarat
- Justin Jeremia
- Amalia Ananda Putri

Telkom University  
Bachelor of Data Science  
2026

---

## 📜 License

This repository was developed for academic purposes as part of the **Data Science in Industry** course at Telkom University.
