# 🏠 House Price Prediction using Machine Learning

## 📌 Overview

This project predicts residential house prices using the **Kaggle House Prices: Advanced Regression Techniques** dataset. The project demonstrates an end-to-end machine learning workflow, including data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and prediction generation.

---

## 📂 Dataset

- Source: Kaggle House Prices Competition
- Training samples: 1,460
- Features: 80+
- Target Variable: SalePrice

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 📊 Workflow

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Missing Value Imputation
- Feature Engineering
- Categorical Encoding
- Target Variable Log Transformation
- Model Training
- Cross Validation
- Prediction Generation

---

## ⚙️ Feature Engineering

Created additional features including:

- TotalSF
- HouseAge
- RemodelAge
- GarageAge
- TotalBathrooms
- TotalFinishedSF

Applied log transformation to the target variable to reduce skewness.

---

## 🤖 Model

Random Forest Regressor

Evaluation:
- 5-Fold Cross Validation

---

## 📁 Project Structure

```
house-price-prediction/
│
├── data/
├── notebooks/
├── models/
├── submissions/
├── images/
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
```

### 2. Install the required dependencies

```bash
pip install -r requirements.txt
```

### 3. Download the dataset

Download the **House Prices: Advanced Regression Techniques** dataset from the Kaggle competition page.

Place the files in the following structure:

```
house-price-prediction/
│
├── data/
│   ├── train.csv
│   └── test.csv
```

### 4. Run the notebook

Open `House_Price_Prediction.ipynb` in Jupyter Notebook or VS Code and run all cells sequentially.

### 5. Generate predictions

The notebook will create a `submission.csv` file containing the predicted house prices for the Kaggle test dataset.

## 📌 Future Improvements

- Hyperparameter tuning using GridSearchCV
- XGBoost and LightGBM implementation
- Advanced feature selection
- Model deployment using Streamlit or Flask

---

## 📜 License

This project is intended for educational and portfolio purposes.
Dataset belongs to the Kaggle House Prices competition.
