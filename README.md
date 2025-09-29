# project_paisa_bazaar
##  Project Overview
This project focuses on **predicting customer credit score categories** (Good, Standard, or Poor) using machine learning. By leveraging customer financial history, the system aims to help financial service platforms like **PaisaBazaar** automate credit risk evaluation, reduce manual verification, and improve the accuracy of financial recommendations.

---

##  Objectives
- Perform **Exploratory Data Analysis (EDA)** to uncover trends and patterns in customer data.  
- Build and evaluate **classification models** for credit score prediction.  
- Provide **visual insights and actionable findings** for decision-makers.  
- Enhance financial recommendations with data-driven predictions.  

---

##  Project Structure

```
project_paisa_bazaar/
│── Paisabazaar (PPT)
│── project_paisa_bazaar # Jupyter notebooks (EDA + Modeling)
│── dataset-2 / DataSet
│── README.md # Project documentation
```

---

##  Dataset Overview
- Contains customer financial and transactional details.  
- Features include: income, loan history, credit utilization, payment behavior, etc.  
- Target variable: **Credit Score Category** → `Good`, `Standard`, `Poor`.  

---

##  Tech Stack
- **Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Environment**: Jupyter Notebook  

---

## Exploratory Data Analysis
- Checked for missing values and outliers.  
- Visualized key financial attributes.  
- Discovered patterns in repayment history, utilization rate, and income distribution.  

---

##  Modeling Approach
- Applied multiple **classification algorithms** (e.g., Logistic Regression, Random Forest, XGBoost).  
- Performed **data preprocessing**: handling missing values, scaling, and encoding.  
- Evaluated models using **accuracy, precision, recall, F1-score, and confusion matrix**.  

---

##  Results & Insights
- Identified the most influential features affecting credit scores.  
- Achieved strong classification accuracy (details in notebook).  
- Credit score prediction helps automate **risk assessment** for financial institutions.  

---

##  How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/paisa-bazaar-credit-score.git
   cd paisa-bazaar-credit-score
