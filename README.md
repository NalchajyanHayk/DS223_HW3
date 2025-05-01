# Homework 3: Survival Analysis – Marketing Analytics

**Author**: Hayk Nalchajyan  
**Course**: DS223 Marketing Analytics  
**Topic**: Survival Analysis and Customer Lifetime Value (CLV)

---

## 📘 Overview

This notebook applies **Survival Analysis** techniques to model customer retention, assess customer lifetime value, and support marketing decision-making. It explores a range of **parametric and non-parametric models** for estimating survival functions and evaluates them for accuracy and interpretability.

---

## 📊 Key Components

### ✅ Parametric AFT Models
- Models used: **Weibull**, **Exponential**, **LogNormal**, **LogLogistic**, **Generalized Gamma**, **Spline**, **Piecewise Exponential**, **Mixture Cure**, **BFH**.
- Tasks:
  - Model fitting and comparison.
  - Survival curve visualization.
  - Feature selection and final model choice.

### ✅ Non-Parametric Models
- **Kaplan-Meier Fitter**
- **Nelson-Aalen Fitter**

### ✅ Model Selection
- The **Weibull model** was selected as the final model based on goodness-of-fit and interpretability.

---

## 💰 Customer Lifetime Value (CLV) Estimation

CLV was calculated for **male and female segments**:
- Revenue assumption: **$50/month**
- Results:
  - **Female CLV**: $2762.91
  - **Male CLV**: $2757.21

These findings suggest that female customers show slightly **higher retention**, helping businesses target more valuable segments.

---

## 📌 Conclusion

This notebook demonstrates a comprehensive application of survival models to estimate retention and lifetime value, supporting data-driven marketing strategies.

---

## ⚙️ Setup and Execution Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/NalchajyanHayk/DS223_HW3.git
cd <your-repo-directory>
```

### 2. Create and Activate a Virtual Environment
```bash
python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Jupyter Notebook
```bash
jupyter notebook DS223_Marketing_Analytics_HW3.ipynb
```