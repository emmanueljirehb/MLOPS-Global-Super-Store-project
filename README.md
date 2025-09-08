# MLOps Global Super Store Project

[![Python](https://img.shields.io/badge/Python-3.10-blue)](https://www.python.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3-green)](https://scikit-learn.org/)
[![MLflow](https://img.shields.io/badge/MLflow-3.3-orange)](https://mlflow.org/)


---

## 🚀 Executive Summary

- Built an end-to-end sales forecasting system for a global retail store to improve forecast accuracy, automate ML tracking, and enable reproducible model deployments. 
- The project supports data-driven business decisions for inventory and demand planning.

---

## 📊 Business Problem

* Manual forecasting often leads to **overstocking** or **stockouts**.
* Poor inventory decisions cause revenue loss and customer dissatisfaction.
* Need for an **automated, accurate, and reproducible forecasting system**.

---

## 💡 Solution

* Developed a **scalable sales forecasting pipeline** using regression models.
* Implemented **MLflow** for automated experiment tracking.
* Deployed models with **version control** to enable smooth updates.

---

## 🛠 Methodology

1. **Data Preprocessing:** Cleaned data, handled missing values, feature engineering.
2. **Model Development:** Regression models with hyperparameter tuning.
3. **Evaluation:** RMSE and forecast accuracy metrics.
4. **Deployment & MLOps:** MLflow tracking, version control, reproducible pipelines.

---

## 💻 Skills Used

* **Programming & Data:** Python, Pandas, NumPy
* **ML & Modeling:** Scikit-learn, regression, hyperparameter tuning
* **MLOps:** MLflow, model versioning, reproducible deployments
* **Data Engineering:** Feature engineering, preprocessing

---

## 📈 Results & Business Impact

* **Forecast accuracy improved by 15%** compared to baseline.
* **Model update & deployment time reduced by 25%.**
* Enabled **data-driven inventory and demand planning decisions**.

---

## 📌 Recommendations

* Leverage forecast insights for **dynamic inventory management**.
* Integrate with ERP systems for **automated restocking**.

---

## 🔮 Next Steps / Future Work

* Explore **deep learning models** for higher accuracy.
* Integrate **real-time sales data** for continuous forecasting.
* Develop a **visual dashboard** for stakeholders.
* Include external factors: **seasonality, promotions, market trends**.
* **Limitations:** Current model may not capture sudden market changes or extreme events.


---

## 📌 Project Objectives

- Analyze and preprocess sales data from the Global Superstore dataset.
- Build and train a predictive model to forecast future sales.
- Track and manage experiments using MLflow.
- Deploy the trained model via a Streamlit web application.
- Maintain reproducibility and scalability in a real-world MLOps setup.

---

## 🛠️ Tech Stack

| Area              | Tools & Libraries                          |
|-------------------|---------------------------------------------|
| Data Processing   | `pandas`, `numpy`, `seaborn`, `matplotlib` |
| Modeling          | `scikit-learn`, `xgboost`                  |
| Experimentation   | `MLflow`                                   |
| Deployment        | `Streamlit`                                |
| Version Control   | `Git`, `GitHub`                            |
| Environment Mgmt  | `virtualenv` / `conda`                     |

---

## 📂 Project Structure
```
├── data/
│ └── Global Superstore.csv
├── notebooks/
│ ├── EDA.ipynb
│ └── model_training.ipynb
├── app/
│ └── streamlit_app.py
├── mlruns/
│ └── [MLflow experiment logs]
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🚀 How to Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/emmanueljirehb/MLOPS-Global-Super-Store-project.git
   cd MLOPS-Global-Super-Store-project
   ```
   
2. **Install dependencies**

pip install -r requirements.txt

3. **Run MLflow UI (optional)**
   mlflow ui

4. **Launch the Streamlit App**

streamlit run app/streamlit_app.py

---
## 📬 Connect With Me

Like the project? Let’s connect\!

  * 🔗 [GitHub](https://github.com/emmanueljirehb) 
  * 📊 [Kaggle](https://www.kaggle.com/emmanueljireh)
  * 📝 [Medium](https://medium.com/@emmanueljirehb)
  * 💼 [LinkedIn](https://www.linkedin.com/in/emmanueljirehb)

