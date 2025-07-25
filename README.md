# insurance-cost-prediction-ml

# Medical Insurance Cost Prediction using Linear Regression & Random Forest

This project aims to predict the **medical insurance costs** of individuals based on demographic and lifestyle features using **Linear Regression** and **Random Forest Regression** models. This notebook covers data preprocessing, model training, evaluation, and comparison of both models.

## 📌 Project Overview

Medical insurance costs are influenced by several factors such as age, BMI, smoking status, and more. Accurately predicting these costs can help insurance companies and individuals better understand pricing structures.

In this project, we:
- Analyze the dataset
- Perform data cleaning and visualization
- Build two predictive models:
  - Linear Regression
  - Random Forest Regressor
- Evaluate and compare the models using metrics like RMSE

## 📂 Files

- `medical_insurance_linear_regression_random_forest.ipynb` – Main Google colab Notebook containing the code, plots, and outputs.

## 📊 Dataset

The dataset is taken from the [Kaggle Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance) and includes the following features:
- `age` – Age of the individual
- `sex` – Gender
- `bmi` – Body Mass Index
- `children` – Number of children covered by health insurance
- `smoker` – Smoking status
- `region` – Residential area
- `charges` – Medical insurance cost (target variable)

## 🔧 Tools & Technologies Used

- Python 🐍
- Pandas
- Numpy
- Matplotlib & Seaborn (for visualization)
- Scikit-learn (for model building)

## 🧠 Machine Learning Models

### 1. Linear Regression
- Interpretable baseline model.
- Assumes a linear relationship between features and the target.

### 2. Random Forest Regressor
- Ensemble model using decision trees.
- Captures non-linear relationships and generally performs better than linear models.

## 📈 Model Evaluation

Models were evaluated using:
- Root Mean Squared Error (RMSE)

## 📚 Conclusion

- **Random Forest Regressor** outperformed Linear Regression in terms of evaluation metrics.
- Feature importance analysis showed that **smoking status**, **age**, and **BMI** are the most influential factors in predicting insurance cost.


## ✍️ Author

Arya Aji – [LinkedIn](https://www.linkedin.com/in/arya-aji-683639257/?originalSubdomain=in) | [GitHub](https://github.com/aryaaaji)

---

⭐ If you find this project useful, feel free to star the repository!
