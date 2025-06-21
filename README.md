# 📘 Yes Bank Stock Price Prediction using Regression

This project is about predicting the **closing price** of Yes Bank's stock using **regression models**.  
The dataset contains monthly stock prices from **2005 to 2020**, and various ML models have been applied to forecast the monthly closing price.

---

## 📁 Project Files

- ✅ Google Colab Notebook  
- ✅ CSV Dataset  
- ✅ Project Summary  
- ✅ Presentation Video  

---

## 📊 Dataset Details

📌 File: `data_YesBank_StockPrices.csv`  
➡️ This file contains monthly stock price data of Yes Bank from 2005 to 2020.  
➡️ It includes the following columns:

- Date  
- Open Price  
- High Price  
- Low Price  
- Close Price  

🗂️ This dataset was used to train and test different regression models for predicting the closing price.

---

## 📍 Problem Statement

Yes Bank, a well-known private bank in India, experienced major financial disruption especially after 2018 due to a fraud case involving Rana Kapoor.  
This project aims to:

- Analyze how such events affected stock price  
- Predict monthly **closing price** using historical data  
- Evaluate different regression models to identify the best one

---

## 🛠️ Steps Followed

### 1️⃣ Data Collection
Collected historical monthly stock data of Yes Bank from Jan 2005 to Sep 2020.

### 2️⃣ Data Cleaning
- Removed missing values  
- Checked for outliers  
- Scaled features where necessary

### 3️⃣ Model Building
Applied the following regression models:

- Linear Regression  
- Ridge Regression  
- Lasso Regression  
- ElasticNet  
- KNN Regressor  
- Random Forest Regressor

### 4️⃣ Evaluation
Used the following metrics:

- MAE (Mean Absolute Error)  
- RMSE (Root Mean Squared Error)  
- R² Score (Accuracy)

### 5️⃣ Conclusion
- ✅ **KNN Regressor** gave the highest accuracy  
- 🔁 But **Random Forest** performed better in terms of generalization and training time  
- 📌 Both models performed well on test data

---

## 🔧 Tech Stack

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Plotly  
- Google Colab

---

## ✅ Conclusion

After trying different regression models, we observed that **KNN Regressor** gave the best accuracy in predicting the stock’s closing price.  
However, **Random Forest** was more reliable for cross-validation and faster in execution.

This project shows how machine learning can help understand and forecast stock trends even in volatile financial conditions.

---

## 🙋‍♂️ Created By: Shivam Shashank

📧 Email: `shivamshashankofficial@gmail.com`  
🔗 GitHub: [ShivamShashank](https://github.com/ShivamShashank11)  
🔗 LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/shivam-shashank-616957213/)

---

_“Machine learning can’t predict the market perfectly, but it can help us make better decisions.”_
