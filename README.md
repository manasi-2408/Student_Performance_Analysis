# 📊 Student Performance Analysis Project

## 📌 Project Overview

This project analyzes student academic performance using demographic, socioeconomic, and academic preparation factors. The analysis combines **Python-based Exploratory Data Analysis (EDA)** and an **interactive Power BI dashboard** to uncover key insights affecting student outcomes in **Math, Reading, and Writing**.

---

## 🎯 Project Objectives

* Analyze student performance across different demographic groups
* Measure the impact of test preparation on overall academic performance
* Understand how socioeconomic factors such as lunch type and parental education affect scores
* Present insights using clear visualizations and an interactive dashboard

---

## 🗂️ Dataset Description

The dataset contains student-level academic and background information, including:

* **Academic Scores:** Math Score, Reading Score, Writing Score
* **Demographics:** Gender, Race/Ethnicity
* **Socioeconomic Factors:** Lunch Type, Parental Level of Education
* **Academic Support:** Test Preparation Course

Each row represents an individual student.

---

## 🧹 Data Cleaning & Preparation

The following preprocessing steps were performed using Python:

* Renamed columns for better readability
* Standardized categorical values (case formatting)
* Consolidated parental education categories
* Treated missing values in *Test Preparation* as **"Not Completed"**
* Verified and corrected data types
* Saved a cleaned version of the dataset for visualization and reporting

---

## 📊 Exploratory Data Analysis (EDA)

EDA was conducted using **Pandas, Matplotlib, and Seaborn**, covering:

* Gender-wise performance comparison
* Test preparation vs academic performance
* Lunch type impact on student scores
* Parental education influence on performance
* Score distributions, correlations, and outlier detection

---

## 📈 Power BI Dashboard

An interactive Power BI dashboard was created to visualize key insights:

* KPI cards for average Math, Reading, and Writing scores
* Overall average score comparison by test preparation status
* Performance comparison by gender and lunch type
* Interactive filters for parental education and race

📸 **Dashboard Preview:**
`images/img.png`

---

## 🔍 Key Insights

* Students who completed test preparation scored significantly higher overall
* Female students performed better in Reading and Writing
* Lunch type (as a socioeconomic indicator) impacts academic performance
* Parental education shows a moderate influence on student outcomes
* Math, Reading, and Writing scores are strongly correlated

---

## 📄 Project Report

Detailed project reports are available in the repository:

* 📄 **PDF:** `reports/student_analysis.pdf`
* 📝 **DOCX:** `reports/student_analysis.docx`

The report explains the analysis, insights, and conclusions in detail.

---

## 🛠️ Tools & Technologies

* **Python:** Pandas, NumPy, Matplotlib, Seaborn
* **Power BI**
* **Jupyter Notebook**
* **Git & GitHub**

---

## 📁 Repository Structure

```
Student_Performance_Analysis/
├── data/
│   └── StudentsPerformance.csv
├── notebooks/
│   ├── data_cleaning.ipynb
│   └── visualization.ipynb
├── powerbi/
│   └── student_analysis.pbix
├── images/
│   └── img.png
├── reports/
│   ├── student_analysis.docx
│   └── student_analysis.pdf
├── README.md
```

---

## 🚀 How to Use This Project

1. Clone the repository:

```bash
git clone https://github.com/manasi-2408/Student_Performance_Analysis.git
```

2. Open and run the notebooks inside the `notebooks/` folder
3. Open the Power BI file (`.pbix`) to explore the interactive dashboard
4. Read the detailed report for complete insights

---

## 📌 Conclusion

This project demonstrates an end-to-end data analysis workflow — from data cleaning and exploration to visualization and reporting. The insights highlight the importance of academic preparation and socioeconomic factors in student performance and support data-driven decision-making in education.

---

⭐ *If you found this project useful, feel free to star the repository.*

---

### 👩‍💻 Author

**Manasi**
GitHub: [https://github.com/manasi-2408](https://github.com/manasi-2408)
student_analysis
