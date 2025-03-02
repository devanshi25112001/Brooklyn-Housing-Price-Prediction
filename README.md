# 🏡 Brooklyn Housing Price Prediction (2016-2020)
📍 **Statistical Analysis | Linear Regression | Feature Engineering | Real Estate Analytics**

## 📌 Project Overview  
This project analyzes **real estate purchase data** in **Brooklyn (2016-2020)** to develop a **linear regression model** that explains **housing prices**. The model evaluates factors like **property type, size, location, and tax class**, ensuring optimal predictive performance.

✅ **Data Source**: Real estate transaction records from **NYC Open Data**  
✅ **Tech Stack**: R, Linear Regression, Feature Engineering, Exploratory Data Analysis (EDA)  
✅ **Goal**: Explain housing price variations using **statistical modeling**  

---

## 📊 Data Processing & Feature Engineering  
- **📥 Data Import**: Merged **5 CSV files** containing property sales data (2016-2020)
- **🧹 Data Cleaning**: Standardized column names, removed missing values, and ensured **consistency across years**.  
- **🏠 Data Filtering**: Focused on **single-family residences & condos** (Building class: **A** or **R**).  
- **📐 Feature Engineering**: Created **new predictors, interaction terms, and polynomial features** to improve model performance.  
- **🚀 Final Dataset**: ~**19,000 observations**  
 ## 📖 Additional Resources  
- 📂 **Building Classification Codes**: [View the Codebook](https://www.nyc.gov/assets/finance/jump/hlpbldgcode.html)  
---

## 📈 Model Development & Performance  
### 📌 Linear Regression Model
- **Target Variable**: Sale Price  
- **Predictors**: Neighborhood, square footage, tax class, building class, year built, etc.  
- **Adjusted R²**: **0.62**  
- **RMSE**: **$438,000**  

### 📉 Model Optimization  
- **Removed non-competitive sales** (e.g., inherited properties, non-market transactions).  
- **Log transformations** applied for skewed variables.  
- **Checked OLS assumptions** (multicollinearity, heteroskedasticity).  

---

## 📂 Files & Submission  
📄 `Devanshi_Ledwani_stats_final.R` → R script for **data processing & model building**  
📂 `Devanshi.RDS` → Saved **regression model & dataset**  

---

## 📌 Results & Key Takeaways  
- ✅ **Successfully predicted Brooklyn housing prices** using a **parsimonious linear regression model**.  
- ✅ **Achieved an RMSE under $450,000** while maintaining **high model interpretability**.  
- ✅ **Feature selection & data cleaning significantly improved model accuracy**.  

---

## 📩 Contact & Contributions  
📧 **Email:** devanshi1@uchicago.edu  
🔗 **LinkedIn:** [Devanshi Ledwani](https://linkedin.com/in/devanshi-ledwani)  
💻 **GitHub:** [GitHub Profile](https://github.com/devanshi25112001)  

🚀 **Feel free to explore, suggest improvements, or contribute!** 🎯  

