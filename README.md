# 🏡 Property Price Prediction Model

## 📖 Overview
This project involves developing a machine learning model to predict residential property prices in Cook County, Illinois, using a dataset of property features. A Random Forest algorithm was used to build the model. The project covers data cleaning, feature engineering, model training, and evaluation. Python libraries like `pandas`, `scikit-learn`, and `matplotlib` were employed for data preprocessing, model building, and visualization.

---

## 🎯 Key Objectives
1. Predict property prices using a Random Forest model.
2. Perform data cleaning and feature engineering to improve model accuracy.
3. Evaluate model performance using metrics like Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).
4. Visualize the predictions versus actual property prices.

---

## 🔑 Highlights
### Data Preprocessing
- **Data Cleaning**: Removed duplicates, handled missing values with median imputation, and addressed outliers.
- **Feature Engineering**: Created derived variables such as price per square foot and tax rate.
  
### Model Development
- **Algorithm Used**: Random Forest
- **Metrics**: Evaluated model performance using MSE, RMSE, and Mean Absolute Percentage Error (MAPE).

### Evaluation
- **Visualization**: Plotted actual vs. predicted property prices to assess the model’s accuracy.

---

## 🛠 Tools and Technologies
- **Python**: Data preprocessing and model building using libraries such as `pandas`, `scikit-learn`, and `matplotlib`.
- **Dataset**: Property dataset containing 50,000 training records and 10,000 test records.

---

## 🎨 Visualizations
- **Predicted vs Actual Property Prices**: Scatter plot to visually compare the predicted property prices with the actual values.
- **Feature Impact**: Visualizations showing the importance of different features like building coverage ratio, price per square foot, and tax rate in predicting property prices.

---

## 📈 Conclusion
The Random Forest model provided a robust prediction of property prices with strong accuracy. Key features, including price per square foot and tax rate, played an important role in predicting the final property value. The visualizations offer valuable insights into model performance, confirming its efficacy in price prediction.

---

## 📂 Repository Contents
- **property_price_prediction.py**: Python script containing the data preprocessing, model training, and evaluation steps.
- **property_data.csv**: The dataset used for training and testing the model.
- **predictions.csv**: The output file containing predicted property prices.
- **README.md**: Project documentation.
