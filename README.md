# Gold Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts gold prices using historical financial market data and machine learning.

The project analyzes relationships between gold prices and selected financial indicators, including the S&P 500 Index (SPX), United States Oil Fund (USO), Silver (SLV), and EUR/USD exchange rate.

A Random Forest Regressor is trained to predict the gold price (GLD) based on these market features.

## 🎯 Objectives

- Analyze historical gold price data
- Perform data exploration and preprocessing
- Study correlations between financial variables
- Select relevant features for prediction
- Train a machine learning regression model
- Evaluate model performance using R² score
- Compare actual and predicted gold prices

## 📊 Dataset

The dataset contains **2,290 records and 6 columns**:

| Feature | Description |
|---|---|
| Date | Historical date |
| SPX | S&P 500 Index |
| GLD | Gold price / target variable |
| USO | United States Oil Fund |
| SLV | Silver price |
| EUR/USD | EUR to USD exchange rate |

## 🛠️ Technologies & Libraries

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## 🔍 Project Workflow

1. Import required libraries
2. Load the historical gold price dataset
3. Explore the dataset
4. Check dataset dimensions and data types
5. Check for missing values
6. Generate statistical summaries
7. Analyze feature correlations
8. Separate features and target variable
9. Split the dataset into training and testing sets
10. Train a Random Forest Regression model
11. Generate predictions
12. Evaluate model performance
13. Compare actual and predicted gold prices

## 🤖 Machine Learning Model

### Random Forest Regressor

A Random Forest Regressor is used to predict the gold price.

**Model configuration:**

- Number of estimators: 100
- Test size: 20%
- Random state for train-test split: 2

## 📈 Model Performance

The model achieved an **R² score of 0.9895** on the test dataset.

This indicates a strong fit between the model's predictions and the actual target values within the evaluated dataset.

## 📉 Actual vs Predicted Values

The project includes a visualization comparing the actual gold prices with the prices predicted by the Random Forest model.

## 📓 Google Colab Notebook

The complete implementation is available in:

`Gold_Price_Prediction.ipynb`

The notebook contains the complete data analysis, model training, predictions, evaluation, and visualization.

## 🚀 How to Run

1. Clone or download this repository.
2. Open `Gold_Price_Prediction.ipynb`.
3. Open the notebook using Google Colab or Jupyter Notebook.
4. Make sure the dataset file is available.
5. Run the notebook cells sequentially.

## 👨‍💻 Author

**Devi Naga Charan Vasanthala**

Data Analytics & Machine Learning

---

⭐ If you find this project useful, consider giving the repository a star.
