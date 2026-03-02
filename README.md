# Bank-Marketing-Campaign-analysis

---

## 📌 Project Overview

This project analyzes a real-world bank marketing dataset to evaluate funnel performance and customer conversion effectiveness.

The goal is to simulate a performance marketing or growth analytics role by:

- Cleaning and structuring campaign data
- Measuring conversion rates
- Identifying drop-off points
- Comparing performance across channels and time periods
- Providing actionable business recommendations

The dataset represents a direct marketing campaign where customers were contacted to subscribe to a term deposit product.

---

## 🎯 Project Objectives

As part of this analysis, the following tasks were completed:

- Structured raw campaign data into funnel metrics
- Calculated overall conversion rate
- Identified funnel drop-offs
- Compared channel performance (cellular vs telephone)
- Analyzed month-wise campaign performance
- Evaluated campaign intensity impact
- Delivered strategic recommendations to improve conversions

---

## 🛠 Tools & Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- VS Code (Jupyter Notebook Extension)

---

## 📂 Dataset Description

Dataset: **Bank Marketing Dataset (UCI Repository)**

Each row represents a customer contact attempt.

Key columns:

- `contact` → Communication channel (cellular / telephone)
- `month` → Month of contact
- `campaign` → Number of contacts performed during campaign
- `y` → Target variable (yes = subscribed, no = not subscribed)

---

## 🔎 Funnel Definition

For this project, the funnel stages were defined as:

| Funnel Stage | Dataset Meaning |
|--------------|-----------------|
| Traffic      | Total customer contacts |
| Conversion   | Customers who subscribed (`y = yes`) |

---

## 📊 Key Analysis Performed

### 1️⃣ Overall Conversion Rate

- Total Contacts = All campaign records
- Total Conversions = Customers who subscribed
- Conversion Rate = (Conversions / Contacts) × 100

**Finding:**  
The campaign conversion rate is relatively low, indicating a high drop-off between contact and subscription.

---

### 2️⃣ Funnel Drop-Off Analysis

- Drop-offs calculated as:
  
  Drop-off = Total Contacts − Total Conversions

**Insight:**  
A significant percentage of customers did not convert, highlighting opportunities for targeting optimization.

---

### 3️⃣ Channel Performance Analysis

Compared conversion rates between:

- Cellular
- Telephone

**Finding:**  
Cellular communication showed higher conversion rates compared to telephone.

**Business Insight:**  
Mobile-based outreach appears more effective and should receive higher budget allocation.

---

### 4️⃣ Campaign Intensity Analysis

Analyzed impact of number of contact attempts (`campaign` variable).

**Insight:**  
Excessive repeated contacts do not necessarily improve conversion and may negatively affect customer experience.

---

### 5️⃣ Month-Wise Performance

Evaluated conversion rates across different months.

**Insight:**  
Certain months demonstrate higher conversion rates, indicating potential seasonal or behavioral patterns.

---

## 📈 Key Business Insights

- Majority of customers drop off after initial contact
- Cellular channel outperforms telephone outreach
- Repeated campaign contacts have diminishing returns
- Conversion performance varies by month
- Better targeting could significantly improve ROI

---

## 💡 Strategic Recommendations

### 🎯 1. Prioritize High-Performing Channels
Shift more marketing budget toward cellular communication.

### 🎯 2. Optimize Contact Frequency
Limit excessive follow-ups to avoid customer fatigue.

### 🎯 3. Improve Targeting Strategy
Use data-driven segmentation to contact high-probability customers.

### 🎯 4. Seasonal Budget Allocation
Increase marketing efforts during historically high-conversion months.

### 🎯 5. Implement Predictive Modeling
Develop a machine learning model to predict subscription likelihood before outreach.

---

## 📊 Business Impact

This analysis helps the organization:

- Improve marketing ROI
- Reduce campaign waste
- Increase subscription conversions
- Optimize channel strategy
- Make data-driven growth decisions

---

## 🚀 How to Run the Project

1. Install required libraries:

```
pip install pandas numpy matplotlib seaborn
```

2. Extract the dataset ZIP file.
3. Load `bank-additional-full.csv` into Jupyter Notebook.
4. Run all analysis cells sequentially.

---

## 🏆 Skills Demonstrated

- Funnel Analysis
- Conversion Rate Calculation
- Drop-Off Analysis
- Channel Performance Evaluation
- Campaign Effectiveness Analysis
- Business Insight Generation
- Marketing Analytics Thinking

---

## 📌 Project Type

- Marketing Analytics Case Study  
- Growth & Performance Analysis  
- Data Analyst Portfolio Project  
- Funnel Optimization Project  

---

## 👨‍💻 Author

pranay wadhai  
Aspiring Data Analyst | Marketing Analytics | Python  

---
