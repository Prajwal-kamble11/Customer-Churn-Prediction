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
```
├── app.py # Streamlit app
├── model.h5 # Trained churn prediction model
├── scaler.pkl # Saved StandardScaler
├── onehot_encoder_geo.pkl # OneHotEncoder for Geography
├── label_encoder_gender.pkl # LabelEncoder for Gender
├── requirements.txt # Python dependencies
└── README.md # Project documentation

```
---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer-churn-prediction.git
   cd customer-churn-prediction
   ```
2. Create a virtual environment (recommended):
     ```bash
     python -m venv venv
     ```
3. Activate the virtual environment:
   - On Mac/Linux:
      ```bash
      source venv/bin/activate
      ```
   - On Windows:
      ```bash
      venv\Scripts\activate
      ```
4. Install dependencies:
     ```bash
     pip install -r requirements.txt
     ```
--- 

▶️ Usage

Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
 
