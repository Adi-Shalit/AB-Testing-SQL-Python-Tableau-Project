# AB Testing SQL Python Tableau Project
This repository contains a complete end-to-end A/B testing analysis pipeline combining SQL, Python, and Tableau, built around a real Kaggle dataset comparing two marketing campaigns (Control vs. Test).

![AB Testing Performance Dashboard](https://github.com/user-attachments/assets/f6fcaa79-b650-4e20-bcc2-f1a2488257c9)

---

## Project Objective

The purpose of this project is to **analyze and compare the performance of two marketing campaigns (Control and Test)** to determine which performs better across multiple key performance indicators (KPIs) such as conversion rate, cost per purchase, and click-through rate. This is done through **statistical testing**, **SQL-based aggregation**, and **interactive visualization** in Tableau to support data-driven decision-making.

---

## Files Included

- **Step 1**: `AB Testing Preparation and t-Test Python.ipynb` – Jupyter Notebook with data cleaning, exploration, and hypothesis testing using t-tests.
- `AB_data_for_Analysis.csv` – Merged and cleaned dataset used for SQL queries and Tableau dashboard.
- **Step 2**: `AB Testing SQL Analysis.ipynb` – SQL analysis in Jupyter Notebook on the cleaned dataset using `pandasql` to extract KPIs and conversion metrics.
- **Step 3**: `AB Testing Performance Dashboard.png` – Tableau visualization on the cleaned dataset comparing campaign performance over time and across metrics.
  [link to the Tableau Public dashboard](https://public.tableau.com/app/profile/adi.shalit/viz/ABTestingPerformance/ABTesting?publish=yes)
- `control_group.csv` – Raw dataset of the control group.
- `test_group.csv` – Raw dataset of the test group.


---

## Tools Used

- **Python**: `Pandas`, `NumPy`, `SciPy (stats)`, `pandasql`
- **Jupyter Notebook**: Used for both Python and SQL queries
- **Tableau**: Interactive dashboard for data visualization and trend analysis

---

## Key Project Features

- Data cleaning and validation of raw A/B test datasets  
- Hypothesis testing (two-sample t-tests) on purchases
- SQL queries for campaign KPI aggregation  
- Tableau dashboard showcasing trends, comparisons, and metrics

---

## Acknowledgments

The dataset used in this project was obtained from [Kaggle](https://www.kaggle.com/datasets/amirmotefaker/ab-testing-dataset).
Special thanks to the original data contributors who compiled and shared the Google Play Store data, enabling this analysis.
