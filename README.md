# 💄 Cosmetics Product Analysis Project

## 📌 Project Overview

This project analyzes cosmetics product data using **pricing, customer ratings, reviews, product usage patterns, and ethical factors**.
The analysis combines **Python-based Exploratory Data Analysis (EDA)** and an **interactive Power BI dashboard** to uncover key insights related to **customer preferences, product positioning, and market trends** in the cosmetics industry.

---

## 🎯 Project Objectives

* Analyze cosmetics products based on **price, rating, and number of reviews**
* Understand **gender-wise and skin-type-wise product preferences**
* Study the impact of **cruelty-free products** on brand usage
* Identify trends in **ingredients, product size, packaging, and usage frequency**
* Present insights using clear visualizations and an interactive dashboard

---

## 🗂️ Dataset Description

The dataset contains product-level information related to cosmetics, including:

* **Product Details:** Product_Name, Brand, Category, Product_Size, Packaging_Type
* **Customer Metrics:** Rating, Number_of_Reviews
* **Pricing:** Price_USD
* **Target Audience:** Gender_Target, Skin_Type
* **Ethical Factors:** Cruelty_Free
* **Usage Patterns:** Usage_Frequency
* **Geography:** Country_of_Origin
* **Ingredients:** Main_Ingredient

Each row represents a single cosmetic product.

---

## 🧹 Data Cleaning & Preparation

The following preprocessing steps were performed using Python:

* Verified dataset shape, columns, and missing values
* Converted **Usage_Frequency** into a numeric scale for analysis
* Converted **Cruelty_Free** into numeric format
* Saved a cleaned version of the dataset for visualization and reporting

---

## 📊 Exploratory Data Analysis (EDA)

EDA was conducted using **Pandas, Matplotlib, and Seaborn**, covering:

* Top 5 most used products
* Category usage by gender
* Skin type vs brand and ingredient preference
* Price vs rating and review analysis
* Product size and packaging preference
* Usage frequency distribution
* Country-wise brand distribution
* Correlation analysis using heatmaps

---

## 📈 Power BI Dashboard

An interactive **Power BI dashboard** was created to visualize key insights:

* KPI cards for **Average Price, Average Rating, and Average Reviews**
* Usage frequency analysis
* Ingredient-wise average price trends
* Product size and packaging distribution
* Gender and skin-type based comparisons
* Interactive filters for **Brand, Category, Product Name, and Country**

📸 **Dashboard Preview:** `images/img.png`

---

## 🔍 Key Insights

* Daily-use products dominate the cosmetics market
* High ratings do not always correspond to higher review counts
* Certain ingredients such as **Retinol and Vitamin C** are priced higher
* Product preferences vary significantly by **skin type and gender**
* Cruelty-free products show strong market presence

---

## 📄 Project Report

Detailed project reports are available in the repository:

* 📄 **PDF:** `reports/cosmetics.pdf`
* 📝 **DOCX:** `reports/cosmetics.docx`

The reports explain the analysis, insights, and conclusions in detail.

---

## 🛠️ Tools & Technologies

* **Python:** Pandas, NumPy, Matplotlib, Seaborn
* **Power BI**
* **Jupyter Notebook**
* **Git & GitHub**

---

## 📁 Repository Structure

```
Cosmetics_Product_Analysis/
├── data/
│   └── cosmetics.csv
├── notebooks/
│   ├── data_cleaning.ipynb
│   └── visualization.ipynb
├── powerbi/
│   └── cosmetics.pbix
├── images/
│   └── img.png
├── reports/
│   ├── cosmetics.docx
│   └── cosmetics.pdf
├── README.md
```

---

## 🚀 How to Use This Project

1. Clone the repository:

   ```
   git clone https://github.com/manasi-2408/Cosmetics_Analysis.git
   ```
2. Open and run the notebooks inside the `notebooks/` folder
3. Open the Power BI file (`.pbix`) to explore the interactive dashboard
4. Read the detailed report for complete insights

---

## 📌 Conclusion

This project demonstrates an **end-to-end data analysis workflow** — from data cleaning and exploratory analysis to visualization and reporting.
The insights help understand **customer behavior, pricing strategies, and product positioning** in the cosmetics industry, supporting data-driven decision-making.

---

⭐ **If you found this project useful, feel free to star the repository.**

---

## 👩‍💻 Author

**Manasi**
GitHub: [https://github.com/manasi-2408](https://github.com/manasi-2408)
