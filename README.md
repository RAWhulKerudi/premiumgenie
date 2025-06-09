<img src="images/premiumgenie.png" alt="premiumgenie" />

# PremiumGenie – Health Insurance Premium Predictor

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green.svg)


**PremiumGenie** is a machine learning-based predictive model that estimates health insurance premiums using customer attributes like age, BMI, smoking habits, medical history, etc. It provides quick, data-driven premium estimates to aid insurers and users in policy planning and pricing decisions.

The application is delivered via an intuitive **Streamlit interface**, allowing users to input personal and medical details and receive real-time premium predictions.

---

## 🔍 Problem Statement

Health insurance pricing can vary significantly based on an individual's profile. PremiumGenie addresses the need for **automated, transparent, and accurate** premium predictions using machine learning. This helps:
- Insurance providers with dynamic pricing
- Applicants with better premium awareness

---

## 🧠 Model & Features

- **Type**: Supervised Regression
- **Input Features**:
  - Age
  - BMI Category
  - Smoking Status
  - Employment Status
  - Marital Status
  - Medical History
  - Income
  - Gender
  - Number of Dependants
  - Genetic Risk
  - Region
  - Insurance Plan 
- **Output**: Estimated premium amount (in ₹)

---

## 🛠️ Tech Stack

- 🐍 **Python**
- 📈 **Machine Learning**: scikit-learn, Linear Regression, XGBoost
- 📊 **Data Analysis**: pandas, NumPy
- 🌐 **Frontend**: [Streamlit](https://streamlit.io)
- 📈 **Visualization**: matplotlib, seaborn

---

## 💡 App Features

- Clean, form-based input interface
- Predicts premium amount in real time


---

## 🚀 Getting Started

1. **Clone the repository:**
    ```commandline
   git clone https://github.com/RAWhulKerudi/premiumgenie.git
   ```
2. **Install dependencies:**
    ```commandline
   pip install -r requirements.txt
   ```
3. **Run the Streamlit app:**
    ```commandline
   streamlit run main.py
   ```

---

## 📂 Project Structure

```
premiumgenie/
│
├── artifacts/                       # Saved predictive model
├── images/                          # UI samples & logos
├── main.py                          # Streamlit UI application
├── prediction_helper.py             # Feature preprocessing and prediction logic
├── README.md
└── requirements.txt
```

---

## 📊 Example Output

> After filling out form inputs:

```
🎯 Predicted Health Insurance Cost: ₹ 5849
```

---

## 🌐 Project Links

- 🔗 GitHub Repo: [GitHub](https://github.com/RAWhulKerudi/premiumgenie)
- 🚀 Live Demo: [Demo](https://premiumgenie-insurance-premium-predictor.streamlit.app/)

---

