# 🚗 Customer Car Price Estimator App

This is a simple Streamlit web application that predicts an estimated car price for a customer based on their **age**, **salary**, and **net worth**. It uses a pre-trained machine learning model to assist car dealerships or advisors in suggesting a suitable car price range for potential buyers.

---

## 📌 Features

- 🔢 User inputs: Age, Salary, and Net Worth  
- 🔍 Model predicts an estimated car price  
- 🎈 Interactive UI built with **Streamlit**  
- ⚙️ ML model and scaler loaded with **joblib**

---

## 🚀 About the App

This project demonstrates how data science and machine learning can be used to support decision-making in a real-world business scenario—car pricing suggestions based on customer profiles.

**How it works:**

1. User inputs customer details (age, salary, net worth)
2. Inputs are scaled using a pre-trained `scaler.pkl`
3. A machine learning model (`model.pkl`) predicts the estimated price
4. The result is displayed on the page with a friendly message

---

## 🧰 Tech Stack

- Python  
- Streamlit  
- Scikit-learn  
- Pandas, NumPy  
- Joblib  
- Jupyter Notebook (for model development)

---

## 🧪 Example Use Case

> A dealership wants to recommend a car to a customer based on their financial profile. This app helps estimate what price range suits them best, automating part of the consultation process.

---

## 📁 Project Structure


---

## ▶️ How to Run the App

### 1. Clone the repository

```bash
git clone https://github.com/Dhirajpawar25/car-price-estimator.git
cd car-price-estimator

pip install -r requirements.txt

streamlit run app.py


