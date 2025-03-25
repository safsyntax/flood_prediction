# 🌊 Flood Prediction using Machine Learning

This project focuses on building a supervised machine learning model to predict the probability of flooding based on environmental data. By leveraging feature selection, linear regression, and performance visualization, the model offers insight into flood risk forecasting.

## 📌 Project Overview

Flooding is a significant environmental threat with serious consequences for infrastructure, agriculture, and public safety. Predictive modeling provides an early warning system to help mitigate flood impact. This project uses historical environmental data to train a linear regression model that forecasts flood probability.

## 🔧 Tools & Technologies

- **Language**: Python  
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`  
- **Model**: Linear Regression  
- **Validation**: 70:30 train-test split with 5-fold cross-validation  
- **Metrics**: R² (R-squared), Mean Squared Error (MSE), Visual Forecasts  

## 🧠 Key Features

### 1. Data Preparation
- Loaded and cleaned dataset using `pandas`.
- Selected relevant features for model training and evaluation.

### 2. Feature Selection
- Used **Recursive Feature Elimination (RFE)** to remove the 10 least impactful features from the initial set of 20.
- Improved model interpretability and reduced overfitting risk.

### 3. Model Training
- Built a **Linear Regression** model using `scikit-learn`.
- Applied a **70:30 train-test split** and validated with **5-fold cross-validation**.

### 4. Evaluation
- Evaluated performance using:
  - **R-squared (R²)** to assess goodness of fit
  - **Mean Squared Error (MSE)** to measure prediction error
  - **Visualizations** to compare predicted vs. actual values

## 📈 Results & Insights

- The final model achieved moderate predictive performance.
- Feature selection streamlined the model while retaining predictive strength.
- Visualization helped highlight discrepancies and trends in predictions.

## 📁 Repository Contents

- [`Individual_ML_Exercise.ipynb`](https://github.com/safsyntax/flood_prediction/blob/ec5420f278fd9d9b8dd0e28fed11c49748e2263e/Individual_ML_Exercise.ipynb): Jupyter notebook containing code for data preparation, feature selection, model building, evaluation, and visualization.

## 🚀 Future Enhancements

- Test non-linear models such as Random Forest, Gradient Boosting, or SVR.
- Integrate real-time sensor data for live flood prediction.
- Deploy the model via a web app or dashboard for accessibility.

## 🌍 Impact

Accurate flood prediction models are essential for disaster preparedness and can significantly reduce economic and human loss. This model offers a foundation for future improvements and real-world applications.

## 📬 Contact

For questions, suggestions, or collaboration, feel free to reach out via [GitHub](https://github.com/safsyntax) or connect on [LinkedIn](https://www.linkedin.com/in/safiya-joseph-39248b51).
