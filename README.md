# 🚗 Car Price Analysis – Understanding the Used Car Market 📊

Gain insights into pricing trends, depreciation patterns, and predictive modeling in the second-hand car market using machine learning and data visualization.

---

## 📌 Project Overview

The used car market is a dynamic industry shaped by various factors such as fuel type, transmission, ownership history, and usage (kilometers driven). This project aims to explore and model the factors influencing **used car selling prices** through a mix of **descriptive analytics**, **exploratory visualizations**, and **regression modeling**.

By cleaning the data and applying machine learning models, we predict the price of a car based on its features and specifications.

---

## 🎯 Objectives of the Study

- Analyze key factors affecting car resale values.
- Identify pricing patterns based on car specifications.
- Predict car prices using regression models.
- Provide actionable insights for car buyers, sellers, and analysts.

---

## ✅ Key Steps in the Project

1. **🧠 Brief Explanation**
   - Overview of the used car market and analysis goals.

2. **📋 Column Descriptions**

| Column         | Description                                                                 |
|----------------|-----------------------------------------------------------------------------|
| `Car_Name`      | Model name of the vehicle                                                  |
| `Year`          | Manufacturing year of the car                                              |
| `Selling_Price` | Price at which the car was sold                                            |
| `Present_Price` | Original showroom price of the car                                         |
| `Kms_Driven`    | Distance the car has been driven                                           |
| `Fuel_Type`     | Type of fuel (Petrol / Diesel / CNG)                                       |
| `Seller_Type`   | Type of seller (Dealer / Individual)                                       |
| `Transmission`  | Gear type (Manual / Automatic)                                             |
| `Owner`         | Ownership history (0 = First owner, 1 = Second owner, etc.)                |

3. **📥 Input Data for Price Prediction**

Example Input:
- Present_Price = 11.23 (Lakhs)
- Kms_Driven = 42,000
- Fuel_Type = Petrol
- Seller_Type = Dealer
- Transmission = Manual
- Owner = 1
- Age = 10 years

➡️ **Goal**: Predict the expected Selling Price using our model.

4. **📚 Import Libraries**
   - `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, etc.

5. **📂 Load Dataset**
   - Load and inspect the structure of the car dataset.

6. **🧹 Data Cleaning**
   - Handle missing values and remove inconsistencies.
   - Sort columns and rows appropriately.

7. **📊 Exploratory Data Analysis (EDA)**
   - Visualize how car age, kilometers, fuel type, etc., affect selling price.
   - Understand relationships using scatter plots and bar graphs.

8. **🔁 Replace Categorical Values**
   - Convert `Fuel_Type`, `Seller_Type`, and `Transmission` to numerical values using encoding.

9. **📈 Model Building and Prediction**
   - **Model 1**: Linear Regression
   - **Model 2**: Linear Regression with normalized/scaled data
   - Predict price of a new car based on specified attributes.
   - Compare predictions from both models.

---

## 🔍 Final Prediction

🚘 **Prediction for the following car:**

- Present Price: ₹11.23 Lakhs  
- KMS Driven: 42,000  
- Fuel Type: Petrol  
- Seller Type: Dealer  
- Transmission: Manual  
- Owner: 1  
- Age: 10 Years  

📌 **Predicted Selling Price:** ₹ _[Your Model Output]_ Lakhs

---

## 💡 Insights & Applications

- Cars with fewer previous owners and lower kilometers tend to retain higher value.
- Manual cars usually have lower resale value than automatic ones in certain markets.
- Fuel Type plays a significant role, especially with fluctuating fuel prices and regulations.

---

## 🏷️ Tags

`#UsedCarMarket` `#CarPricePrediction` `#RegressionModel` `#MachineLearning` `#EDA` `#DataCleaning` `#Python`

---

## 🤝 Contribute

Feel free to fork this repo, open issues, or contribute by enhancing model accuracy or adding more data sources.

