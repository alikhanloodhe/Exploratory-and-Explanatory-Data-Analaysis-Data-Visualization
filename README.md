# 📊 Exploratory Data Analysis on Pakistan’s Largest E-Commerce Dataset

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on *Pakistan’s Largest E-Commerce Dataset* to uncover insights about customer behavior, sales trends, payment preferences, and category-wise performance over multiple years.

The project is structured into **two clearly separated stages**:
1. **Data Cleaning & Preparation**
2. **Exploratory Data Analysis (EDA)**

---

## 📂 Repository Structure
```
├── Data_Cleaning.ipynb
├── EDA.ipynb
└── README.md
```
---

## 📁 Dataset
- **Source:** Kaggle  
- **Dataset:** *Pakistan’s Largest E-Commerce Dataset*  
- Due to file size limitations, the dataset is **not included** in this repository.
- The **Kaggle download link is provided inside `Data_Cleaning.ipynb`**.

---

## 🧹 Step 1: Data Cleaning & Preparation (Run First)
**File:** `Data_Cleaning.ipynb`

This notebook handles real-world data issues, including:
- Missing values and null handling
- Inconsistent categorical values (order status, payment methods)
- Invalid numerical values (negative prices, discounts, totals)
- Redundant and derivable columns
- Data type standardization
- Column renaming for clarity

At the end of this step, a **cleaned dataset** is saved for analysis.

⚠️ **Important:**  
This notebook **must be executed before** running the EDA notebook.

---

## 📈 Step 2: Exploratory Data Analysis (EDA)
**File:** `EDA.ipynb`

This notebook focuses on:
- Order status distribution and success rate analysis
- Category-wise sales trends across years
- Payment method preferences
- Customer tenure and repeat-purchase behavior
- Temporal analysis (monthly and yearly trends)
- Data reduction techniques (aggregation, stratified sampling)

---

## 🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🎯 Key Project Focus
- Handling **realistic, inconsistent large-scale data**
- Clear and meaningful visual storytelling
- Application of **data reduction** to avoid clutter
- **Accessibility-aware visualizations**
  - Colorblind-safe palette
  - Readable labels and annotations
- Ethical handling of consumer transaction data

---

## ▶️ How to Run
1. Run `Data_Cleaning.ipynb`
2. Ensure the cleaned dataset is generated
3. Run `EDA.ipynb`

---

## 📌 Notes
- This project is focused on **data visualization and exploratory insights**, not predictive modeling.
- All visualizations are based on cleaned and reduced data to prevent misleading interpretations.

---

## 📜 License
This project is intended for **educational and academic use only**.
