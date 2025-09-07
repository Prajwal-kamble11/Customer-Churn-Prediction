# 🏦 Customer Churn Prediction

This project predicts **customer churn** (whether a bank customer will leave the bank or not) using **Machine Learning** and **Deep Learning**.  
It includes a **Streamlit web app** for interactive predictions.

---

## 🚀 Features

- Predict customer churn based on input features such as:
  - Credit Score
  - Age
  - Balance
  - Number of Products
  - Has Credit Card
  - Active Membership
  - Estimated Salary
  - Gender
  - Geography
- Uses a trained **TensorFlow/Keras model (`model.h5`)**
- Encodes categorical features with:
  - `OneHotEncoder` for Geography
  - `LabelEncoder` for Gender
- Scales numerical features with `StandardScaler`
- Interactive web interface powered by **Streamlit**

---

## 📂 Project Structure

