# 🛡️ Life Insurance Plan Prediction: Term vs Traditional

Welcome to a machine learning-based project that predicts whether a customer should opt for a **Term Plan** or a **Traditional Plan**, based on demographic, financial, and health-related factors. This project helps insurance companies personalize recommendations and allows users to understand their ideal insurance plan.

## 📊 Dataset Overview

- **Total Records**: 2,999
- **Target**: `Plan` – { `Term Plan`, `Traditional Plan` }
- **Features**: 13
  - 'Name',`Age`, `Annual Income`, `Annual Expense`
  - `Height`, `Weight`, `BMI`
  - `Occupation`, `Medical History`, `Loan History`
  - `Premium Affordability`, `Sum Assured', 'Plan'.

## 🧠 Project Goals

- Analyze customer profiles
- Predict the appropriate life insurance plan
- Assist insurers with targeted policy offerings
- Provide interactive prediction using trained models

## 🔧 Tech Stack

- **Language**: Python  
- **Libraries**:  
  `pandas`, `numpy`, `scikit-learn`, `plotly`, `seaborn`, `lazypredict`  
- **Model**
- `RandomForestClassifier`, `LogisticRegression`, `XGBoost`

## 📌 Key Concepts

- **BMI Calculation**: Derived from height and weight
- **Premium Affordability**: `(Insurance Duration / 100) * (Income - Expense)`
- **Sum Assured**: `Insurance Duration * (Income - Expense)`
- **Occupation Risk**: Categorized into low and high risk (e.g., IT = Low Risk, Construction = High Risk)

## 📈 Data Visualization

- Age vs Annual Income (by Plan)
- BMI Distribution (by Plan)
- Premium Affordability by Medical History
- Plan Distribution Pie Chart
- Sum Assured across Occupations

## 🤖 Model Building

- Feature Selection with `SelectKBest`
- Automated model comparison with `LazyPredict`
- Trained and tested using:
  - Random Forest
  - Extra Trees
  - Logistic Regression etc..
 
  

✅ All top models achieved **good accuracy** on the test set.

## 🧪 Model Performance

| Model                    | Accuracy | F1-Score | Time Taken |
|--------------------------|----------|----------|------------|
| Random Forest            | 95%     | 0.90    | 0.41s      |





