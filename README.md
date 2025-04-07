# 📊 Customer Churn Prediction

A machine learning project to predict customer behavior—specifically whether a customer will **churn**, **stay**, or **join** a telecommunications company—based on a variety of features including demographics, location, subscription details, and more.

---

## 🧩 Problem Statement

The dataset contains detailed records of **7,043 customers** from a **California-based telecommunications company** during **Q2 2022**.  
Each entry includes:

- Customer demographics and location  
- Subscription services and tenure  
- Status for the quarter: `Joined`, `Stayed`, or `Churned`

Additionally, a **Zip Code Population** table provides population estimates for California zip codes to support geographic insights.

The task is to build a predictive model that classifies whether a customer will churn, stay, or join the company based on the provided features.

---

## 🖼️ Project Screenshots

<img src="/assets/1.png" width="400"/> 
<img src="/assets/2.png" width="400"/>  
<img src="/assets/3.png" width="400"/> 
<img src="/assets/4.png" width="400"/>

---

## 📈 Model Performance Overview

| Model                     | Accuracy |
|--------------------------|----------|
| XGBoost Classifier        | **80.86%** |
| Logistic Regression       | 78.28%   |
| Random Forest             | 78.11%   |
| Decision Tree             | 77.29%   |
| Naive Bayes (Gaussian)    | 36.77%   |

> ✅ The XGBoost Classifier provided the best results with an accuracy of **80.86%**.

---

## 🚀 Use Case & Business Value

Predicting customer churn enables proactive business strategies such as:

- 🧑‍💼 Customer success teams reaching out to at-risk clients  
- 🎯 Targeted retention campaigns based on churn likelihood  
- 📉 Reducing overall churn rate and increasing customer lifetime value  

> Understanding churn trends helps assess customer satisfaction and the overall effectiveness of services offered.

---

## 🛠️ How to Run the Code

1. **Clone the repository**
  ```bash
  git clone https://github.com/mishraShilpa-28/customer-churn-prediction.git
  cd customer-churn-prediction
  ```
2. **Run the main notebook** 
Open Churn_Prediction.ipynb in Jupyter Notebook or VSCode and run each cell to:
- Preprocess data
- Train models
- Evaluate performance
- Visualize results

---

## 📂 Folder Structure

```bash
customer-churn-prediction/
│
├── data/                       # Raw and cleaned datasets
│   ├── customer_churn.csv
│   └── zipcode_population.csv
│
├── models/                     # Trained model files (if saved)
│
├── assets/                     # Screenshots and visual assets
│   ├── 1.png
│   ├── 2.png
│   └── ...
│
├── Churn_Prediction.ipynb      # Main Jupyter notebook
├── requirements.txt            # Required Python packages
├── README.md                   # Project documentation
└── LICENSE                     # MIT License
```

---

## 📜 License
This project is licensed under the MIT License.

