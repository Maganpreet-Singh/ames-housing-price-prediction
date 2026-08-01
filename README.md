# 🏠 Ames Housing Price Prediction

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?logo=numpy)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?logo=scikit-learn)
![CatBoost](https://img.shields.io/badge/CatBoost-Gradient%20Boosting-yellow)
![License](https://img.shields.io/badge/License-Educational-green)

A complete **Machine Learning Regression Project** that predicts house sale prices using the **Ames Housing Dataset**. This project demonstrates the entire machine learning workflow—from data preprocessing and exploratory data analysis (EDA) to model training, evaluation, and comparison of multiple regression algorithms.

---

# 📑 Table of Contents

- Project Overview
- Objectives
- Repository Structure
- Dataset Information
- Machine Learning Workflow
- Exploratory Data Analysis
- Data Preprocessing
- Feature Engineering
- Models Used
- Model Evaluation
- Technologies Used
- Installation
- How to Run
- Repository Files
- Results
- Future Improvements
- Learning Outcomes
- Author
- License
- Acknowledgements

---

# 📌 Project Overview

House prices are influenced by numerous factors such as:

- Neighborhood
- Overall Quality
- Living Area
- Garage Capacity
- Basement Area
- Year Built
- Kitchen Quality
- Exterior Quality
- Number of Rooms
- Lot Size
- Sale Condition

The objective of this project is to develop a machine learning model capable of accurately predicting house prices based on these property characteristics.

The project covers every major stage of a real-world machine learning pipeline, making it suitable for learning regression modeling and feature engineering.

---

# 🎯 Objectives

The primary goals of this project are:

- Understand the Ames Housing dataset.
- Perform exploratory data analysis.
- Handle missing values.
- Encode categorical variables.
- Prepare data for machine learning.
- Train multiple regression models.
- Compare model performance.
- Select the best-performing model.
- Analyze important features affecting house prices.

---

# 📂 Repository Structure

```text
ames-housing-price-prediction/
│
├── Images/
│   ├── Distribution plots
│   ├── Count plots
│   ├── Correlation heatmaps
│   ├── Boxplots
│   ├── Scatter plots
│   └── Other EDA visualizations
│
├── catboost_info/
│   └── Automatically generated CatBoost training logs
│
├── AmesHousing.csv
│   └── Original dataset
│
├── Model.ipynb
│   └── Complete machine learning workflow
│
├── Model_Comparison.csv
│   └── Performance comparison of regression models
│
└── README.md
```

---

# 📊 Dataset Information

**Dataset Name:** Ames Housing Dataset

The dataset contains residential house information collected from Ames, Iowa.

It contains various numerical and categorical features describing residential properties.

### Example Features

- Lot Area
- Street
- Neighborhood
- Overall Quality
- Overall Condition
- Year Built
- Year Remodeled
- Roof Style
- Exterior Material
- Basement Quality
- Heating Quality
- Kitchen Quality
- Garage Type
- Garage Area
- Garage Capacity
- Pool Quality
- Fence
- Sale Type
- Sale Condition

### 🎯 Target Variable

**SalePrice**

The goal of regression is to predict this variable.

---

# 🔄 Machine Learning Workflow

The notebook follows the following workflow:

```
Data Collection
        ↓
Data Understanding
        ↓
Exploratory Data Analysis
        ↓
Data Cleaning
        ↓
Missing Value Treatment
        ↓
Feature Engineering
        ↓
Encoding
        ↓
Train-Test Split
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Model Comparison
        ↓
Best Model Selection
```

---

# 📈 Exploratory Data Analysis (EDA)

Several visualizations were created to better understand the dataset.

The analysis includes:

- Distribution plots
- Histograms
- Count plots
- Box plots
- Scatter plots
- Correlation heatmap
- Missing value analysis
- Outlier detection
- Target variable distribution
- Numerical feature analysis
- Categorical feature analysis

All generated plots are stored inside the **Images** folder.

---

# 🧹 Data Preprocessing

The preprocessing stage includes:

- Handling missing values
- Removing unnecessary columns
- Treating categorical variables
- Feature encoding
- Data cleaning
- Splitting features and target
- Train-test split

These preprocessing steps prepare the dataset for machine learning models.

---

# ⚙️ Feature Engineering

Several feature engineering techniques may include:

- Encoding categorical variables
- Handling missing categories
- Selecting relevant features
- Removing redundant information
- Preparing data for regression algorithms

---

# 🤖 Machine Learning Models Used

Multiple regression algorithms were trained and compared.

Examples include:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost
- CatBoost Regressor

The final model is selected based on evaluation metrics.

---

# 📉 Model Evaluation

The regression models are evaluated using metrics such as:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

The comparison of all trained models is stored in:

```
Model_Comparison.csv
```

---

# 🛠 Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- CatBoost

### Development Environment

- Jupyter Notebook

---

# 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/Maganpreet-Singh/ames-housing-price-prediction.git
```

Move inside the repository:

```bash
cd ames-housing-price-prediction
```

Install required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn catboost jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Model.ipynb
```

Run all cells sequentially.

---

# 📁 Repository Files

## 📄 AmesHousing.csv

Contains the original housing dataset.

---

## 📓 Model.ipynb

Contains the complete project including:

- Data Loading
- Data Cleaning
- EDA
- Feature Engineering
- Model Training
- Model Evaluation
- Model Comparison

---

## 📊 Model_Comparison.csv

Stores the performance comparison of all regression models.

Example metrics include:

- Model Name
- R² Score
- MAE
- RMSE
- MSE

---

## 🖼 Images Folder

Contains all visualizations created during exploratory data analysis, including:

- Histograms
- Countplots
- Heatmaps
- Scatter plots
- Box plots
- Distribution plots

---

## 📂 catboost_info

Automatically generated folder created while training CatBoost models.

It stores:

- Training logs
- Learning curves
- Temporary training information

---

# 📈 Results

Different regression algorithms were trained and compared.

The final model was selected based on:

- Highest R² Score
- Lowest MAE
- Lowest RMSE
- Better generalization on unseen data

Complete comparison is available in:

```
Model_Comparison.csv
```

---

# 💡 Future Improvements

Potential improvements include:

- Hyperparameter tuning
- Cross-validation
- Advanced feature engineering
- Feature selection
- Ensemble learning
- SHAP feature importance
- Model explainability
- Deployment using Streamlit
- Flask API deployment
- Docker containerization
- Cloud deployment (AWS, Azure, GCP)

---

# 📚 Learning Outcomes

This project demonstrates practical knowledge of:

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Regression Algorithms
- Model Comparison
- Performance Evaluation
- Machine Learning Workflow
- Python Data Science Libraries

---

# 👨‍💻 Author

**Maganpreet Singh**

Computer Science Engineering Student

Specialization: Artificial Intelligence & Machine Learning

GitHub: https://github.com/Maganpreet-Singh

---

# 📄 License

This project is intended for educational purposes and portfolio demonstration.

Feel free to fork the repository, learn from it, and improve upon it while providing appropriate attribution.

---

# 🙏 Acknowledgements

- Ames Housing Dataset
- Scikit-Learn Documentation
- CatBoost Documentation
- Pandas Documentation
- NumPy Documentation
- Matplotlib Documentation
- Seaborn Documentation
- Python Open Source Community

---

⭐ **If you found this project helpful, consider giving the repository a star!**
