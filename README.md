# 🚗 Vehicle Maintenance Cost Analysis – Python & Machine Learning Project

This project analyzes over **50,000 simulated vehicle maintenance records** to uncover patterns, calculate key performance indicators (KPIs), and build predictive models for cost forecasting and high-cost risk classification. The project is inspired by real-world fleet operations in roles like **Fleet Services Analyst** at companies such as **Lucid Motors, Tesla, and Rivian**.

---

## 📂 Project Overview

| Area | Details |
|------|---------|
| **Dataset** | 50,000+ maintenance records (`.xlsx`) |
| **Tools** | Python, pandas, matplotlib, seaborn, scikit-learn |
| **Models** | Random Forest Regressor & Classifier |
| **Focus** | Maintenance cost trends, KPI breakdowns, predictive ML pipeline |

---

## 🔧 Tools & Libraries

- `pandas`, `numpy` – Data cleaning and transformation  
- `matplotlib`, `seaborn` – Data visualization  
- `scikit-learn` – Machine learning pipeline (regression & classification)  
- `joblib` (optional) – Model saving (not included here but recommended)

---

## 📊 Key KPIs & Visual Insights

The following KPIs were calculated and visualized using `matplotlib` and `seaborn`:

1. **Total Maintenance Cost by Year**
2. **Cost by Service Type** (Preventive, Repair, Inspection)
3. **Cost by Region**
4. **Top 10 Most Expensive Vehicles**
5. **Warranty Status Impact on Cost**
6. **Cost by Part Replaced**

Each visualization includes **clearly labeled bar charts** for clarity and decision-maker readiness.

---

## 🔍 Machine Learning – Maintenance Cost Prediction

### 🎯 Objective:  
Predict the **total service cost** for a given maintenance event using vehicle and service features.

### ✅ Model: `RandomForestRegressor`
- Trained using a `Pipeline` with:
  - One-hot encoding for categorical features  
  - Random forest for regression  
- **Evaluation:**
  - `Mean Absolute Error (MAE)`  
  - `R² Score`

### 🔍 Feature Importance:
Top predictors included:
- `Service_Type_Repair`
- `Vehicle_Age`
- `Part_Replaced`
- `Under_Warranty`

Visualized in a ranked bar chart (Top 15 most important features).

---

## 🧠 Machine Learning – High-Cost Risk Classification

### 🎯 Objective:  
Classify whether a service will cost **more than $1,000**

### ✅ Model: `RandomForestClassifier`
- Target variable: `High_Cost` (1 = Yes, 0 = No)
- Features: Same as regression model
- **Evaluation:**
  - Accuracy  
  - Precision  
  - Recall  
  - Confusion Matrix  
  - Classification Report

---

## 💼 Real-World Applications

- Fleet management teams can use these models to:
  - Forecast budget requirements
  - Identify costly service types or vehicle groups
  - Predict and prevent surprise high-cost service events
- Business analysts can incorporate this into a dashboard or automation tool (e.g., Streamlit, Power BI)

---

## 🚀 Next Steps (Optional Extensions)

- ✅ Save models as `.pkl` using `joblib`
- 🖥 Build a **Streamlit app** to let users simulate service conditions and predict cost or risk
- 🔄 Use **time series models** (e.g., ARIMA, Prophet) for long-term maintenance cost forecasting
- 📊 Deploy as a **Tableau dashboard** for ops stakeholders

---

## 📬 Contact

Feel free to reach out via LinkedIn or GitHub if you’d like to collaborate or have questions about the project.  
Project by [Prachi] – Built to simulate real-world analytics in EV fleet operations.



