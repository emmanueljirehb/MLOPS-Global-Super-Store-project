# MLOPS-Global-Super-Store-project

## 🏬 MLOps - Global Superstore Sales Forecasting

This project demonstrates an end-to-end **MLOps pipeline** for forecasting sales using the **Global Superstore dataset**. It incorporates all critical components of the machine learning lifecycle — from data preprocessing to model deployment — using tools like **MLflow**, **scikit-learn**, and **Streamlit**.

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

## 📊 Results & Insights

- Forecasting model shows improved accuracy using XGBoost over baseline models.

- MLflow helped track and compare various hyperparameter tuning experiments.

- Streamlit app allows user-friendly predictions on new data inputs.

## 📈 MLflow Tracking Example

Experimentation is tracked using MLflow:

 - Parameters (e.g., learning rate, max depth)

 - Metrics (e.g., RMSE, MAE)

 - Artifacts (e.g., trained models)

 - Visualization via MLflow UI

## 📌 Future Improvements

- Integrate Docker for containerized deployment.

- Add CI/CD using GitHub Actions.

- Incorporate model monitoring with Prometheus/Grafana.


## 🙌 Acknowledgements

Thanks to the creators of the Global Superstore dataset and open-source contributors whose tools made this possible.


