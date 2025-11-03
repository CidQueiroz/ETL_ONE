# ETL Project - Customer Churn Analysis for TelecomX

This project aims to perform a complete **ETL (Extraction, Transformation, and Loading)** process and exploratory analysis of customer data from the fictitious company **TelecomX**, aiming to identify the main factors contributing to customer churn and propose strategic recommendations for retention.

## 📁 Project Structure

- **TelecomX_BR.ipynb**: Main notebook containing the entire ETL flow, exploratory analysis, and final report.

- **Other files**: Auxiliary notebooks and datasets for studies and tests.

---
See also: - [![Project Machine_Learning_Alura](https://img.shields.io/badge/github-Machine_Learning_Alura-blue)](https://github.com/CidQueiroz/Machine_Learning_Alura)

---

## 🚀 How to Run

1. **Prerequisites**

Make sure you have Python 3.x installed and the following libraries:

- pandas

- numpy

- matplotlib

- seaborn

- requests

Install the dependencies with:

``bash
pip install pandas numpy matplotlib seaborn requests

2. **Run**

- Open the TelecomX_BR.ipynb file in a Jupyter Notebook environment (VS Code, JupyterLab, etc.) and run the cells sequentially.

## 📊 TelecomX_BR Notebook Flowchart

**Extraction**

- Data is extracted from a public API (JSON hosted on GitHub).

- Uses the requests and pandas libraries to load the data into a DataFrame.

**Transformation**

- Standardization of column names.

- Removal of inconsistent rows and handling of null values.

- Conversion of columns to appropriate types and filling in missing values ​​with the median or mode.

**Loading and Analysis**

- Exploratory data analysis (EDA) with visualizations using matplotlib and seaborn.

- Generation of descriptive statistics, distribution graphs, correlation, and outlier detection.

**Final Report**

- Presentation of key insights on churn.

- Strategic recommendations for reducing customer churn.

## 📈 Key Insights

- Monthly contracts, fiber optic usage, and electronic check payments are strongly associated with churn.

- Customers with shorter contract lengths and higher monthly charges have a greater risk of churn.

## 📝 Recommendations

- Encourage migration to longer contracts.

- Investigate fiber optic customer satisfaction.

- Optimize payment methods, promoting automated options.

- Monitor new customers and those with high charges for proactive retention actions.

## 📚 References

- Data Science Challenge - Alura
- Documentation of the libraries: pandas, matplotlib, seaborn
- Project developed for educational purposes in the context of the Data Science and Artificial Intelligence course.
