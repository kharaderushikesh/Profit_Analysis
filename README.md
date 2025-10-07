# Profit_Analysis
Multiple Linear Regression Project — Predicting company profit based on R&amp;D Spend, Administration, and Marketing Spend. Includes dataset preprocessing, EDA, model training, evaluation (R²=0.95), and visual insights with Power BI and Python.
# 💼 Profit Prediction using Multiple Linear Regression

## 📘 Project Overview
This project analyzes how **R&D Spend**, **Administration**, and **Marketing Spend** impact **Profit** using **Multiple Linear Regression**.  
The analysis includes data cleaning, exploratory data analysis (EDA), model training, evaluation, and business insights.

---

## 📊 Objectives
- Perform multiple linear regression to predict company profit.
- Identify which variables most influence profit.
- Evaluate model performance using **R²** and **RMSE**.
- Visualize relationships using **Matplotlib**, **Seaborn**, and **Power BI/Tableau**.
- Provide business recommendations based on analysis results.

---

## 🧩 Dataset
**File:** `50_Startups.csv` (in this project named `5_6260172351569140005.csv`)  
**Attributes:**
| Feature | Description |
|----------|--------------|
| R&D Spend | Expenditure on Research & Development |
| Administration | Company’s administrative expenses |
| Marketing Spend | Total marketing expenditure |
| Profit | Target variable (dependent) |

---

## 🧮 Model Summary
| Metric | Value |
|--------|--------|
| Algorithm | Multiple Linear Regression |
| R² Score | **0.9507** |
| RMSE | **8855.34** |
| Intercept | **50122.19** |
| Coefficients | R&D=+0.8057, Admin=−0.0268, Marketing=+0.0272 |

### **Regression Equation**
\[
Profit = 50122.19 + 0.8057(R\&D) - 0.0268(Administration) + 0.0272(Marketing)
\]

---

## 🔮 Predictions
| R&D Spend | Administration | Marketing Spend | Predicted Profit |
|------------|----------------|----------------|------------------|
| 21892.92 | 81910.77 | 164270.70 | ₹70,037.90 |
| 23940.93 | 96489.63 | 137001.10 | ₹70,554.57 |

---

## 📈 Visualizations
- 📊 **R&D Spend vs Profit**
- 📈 **Marketing Spend vs Profit**
- 📉 **Administration vs Profit**
- 🔥 **Feature Coefficients Chart**
- 🧠 **Correlation Heatmap**

---

## 🧠 Insights & Recommendations
1. **R&D Spend** has the strongest positive correlation with Profit — increasing R&D investment can maximize returns.  
2. **Marketing Spend** contributes moderately to profit growth — focus on high-performing campaigns.  
3. **Administration** expenses have a weak or negative influence — optimize operational efficiency.  
4. The model explains **95% of variance** in profit (R² = 0.95), indicating high reliability.

---

## ⚙️ Tools & Technologies
- 🐍 **Python** (pandas, numpy, scikit-learn, matplotlib, seaborn)
- 📊 **Power BI / Tableau** for visualization
- 📓 **Jupyter Notebook**
- 💻 **Excel** (optional for regression validation)
