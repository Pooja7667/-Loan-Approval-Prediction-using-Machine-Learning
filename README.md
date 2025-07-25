﻿# -Loan-Approval-Prediction-using-Machine-Learning


 # 🏦 Loan Approval Prediction Project

This project explores and analyzes a bank's loan application dataset to identify key factors influencing loan approvals. Using data science techniques, we built predictive models and visualized trends to support data-driven decision-making.

---

## 📁 Project Structure

loan-approval-project/
│
├── loan_data.csv # Raw dataset
├── loan_analysis.ipynb # Colab or Jupyter Notebook with code
├── output/ # Charts, visuals, or exported reports
├── models/ # Trained model files (if any)
├── README.md # Project documentation

yaml
Copy
Edit

---

## 📊 Problem Statement

The goal is to **predict whether a loan will be approved or not**, based on applicant information like income, credit history, employment status, etc. This helps automate decision-making and reduce manual review time for banks.

---

## 🔧 Tools & Technologies

- **Python** (Pandas, NumPy)
- **Matplotlib**, **Seaborn** for visualization
- **Scikit-learn** for ML modeling
- **Google Colab** or **Jupyter Notebook**
- **Power BI / Excel** for dashboards (optional)

---

## 📌 Key Steps

1. **Data Cleaning & Preprocessing**
   - Handled missing values in columns like `LoanAmount`, `Credit_History`
   - Converted categorical values using label encoding

2. **Exploratory Data Analysis (EDA)**
   - Analyzed patterns between `Loan_Status` and features like:
     - ApplicantIncome
     - Property_Area
     - Education & Credit_History

3. **Model Building**
   - Built classifiers: Logistic Regression, Decision Tree, Random Forest
   - Evaluated using Accuracy, Confusion Matrix

4. **Insights**
   - Credit History had the strongest influence on loan approval
   - Graduate applicants from Urban areas had higher approval rates

---

## 📈 Sample Visuals

![Loan Approval by Credit History](output/credit_history_plot.png)
![Loan Status by Property Area](output/property_area_chart.png)

---

## 🔍 Results

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression| 80.4%    |
| Decision Tree      | 78.9%    |
| Random Forest      | 81.2% ✅ Best |

---

## ✅ Business Recommendations

- Give priority to applicants with strong credit history
- Consider simplifying approval for salaried applicants in urban areas
- Collect more detailed employment & property data for better prediction

---

## 📎 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/poojagupta/loan-approval-project.git
