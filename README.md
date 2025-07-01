# Retail Sales Forecasting Assignment

**Student Name**: Lalit Nayyar  
**Email ID**: lalitnayyar@gmail.com  
**Assignment**: Week 12: Required Assignment 12.2  
**University**: IIMK – Professional Certificate in Data Science and Artificial Intelligence for Managers

## Overview
This project analyzes and forecasts retail sales using Python, pandas, and Facebook Prophet. It includes scenario analysis, business recommendations, and time series forecasting on a real-world retail dataset.

---

## Features
- **Retail Sales Data Analysis:**
  - Aggregation and exploration of transactional retail data.
  - Monthly sales trends and seasonality visualization.
- **Scenario Analysis:**
  - Business-focused scenario planning and recommendations based on data trends.
- **Advanced Forecasting:**
  - Facebook Prophet model for time series forecasting.
  - Visualization of forecast and forecast components (trend, seasonality).
  - Simple forecast accuracy evaluation (MAE).
- **Submission-Ready Notebooks:**
  - Two Jupyter notebooks:
    - `Week12_Assignment12_2_LalitNayyar.ipynb`: Business and scenario analysis, recommendations.
    - `Week12_Assignment12_2_Scenario_Analysis.ipynb`: Technical analysis, Prophet forecasting, evaluation.
- **PDF Export:**
  - Notebooks can be exported to PDF for assignment submission.

---

## Functionality
- **Data Loading:** Reads `retail_sales_dataset.csv` containing transaction-level retail data.
- **Data Aggregation:** Aggregates daily transactions into monthly sales totals for analysis and modeling.
- **Visualization:** Uses matplotlib to plot sales trends and Prophet forecast results.
- **Forecasting:**
  - Prepares data for Prophet (`ds`, `y` columns).
  - Fits Prophet model with yearly seasonality.
  - Forecasts next 6 months of sales.
  - Plots forecast and its components.
- **Evaluation:**
  - Compares actual vs. predicted sales for recent months.
  - Calculates Mean Absolute Error (MAE).
- **Business Recommendations:**
  - Scenario analysis notebook provides actionable insights for business decisions based on data and forecasts.

---

## User Guide

### Prerequisites
- Python 3.9+
- Jupyter Notebook or JupyterLab
- Required Python packages:
  - `pandas`
  - `matplotlib`
  - `prophet`

### Setup
1. **Clone or Download the Repository**
2. **Install Dependencies** (if not already installed)
   ```bash
   pip install pandas matplotlib prophet
   ```
3. **Open Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
4. **Open the Notebooks**
   - `Week12_Assignment12_2_LalitNayyar.ipynb`
   - `Week12_Assignment12_2_Scenario_Analysis.ipynb`

### Running the Analysis and Forecast
1. **Ensure `retail_sales_dataset.csv` is in the project directory.**
2. **Run all cells in the notebooks in order.**
   - For forecasting, ensure Prophet is installed and all code cells execute without error.
3. **View outputs:**
   - Plots and tables will be displayed in the notebook.
   - Forecast plots and evaluation metrics are in the Scenario Analysis notebook.
4. **Export to PDF (optional):**
   - Use `File > Download as > PDF via LaTeX (.pdf)` in Jupyter Notebook, or run:
     ```bash
     jupyter nbconvert --to pdf <notebook_name>.ipynb
     ```

### Troubleshooting
- If you see `ModuleNotFoundError: No module named 'prophet'`, install Prophet using `pip install prophet`.
- If you see a FutureWarning about pandas frequency `'M'`, ensure the code uses `'ME'` for month-end frequency.

---

## Contact
For any issues or questions, please contact the project author or your course instructor.

---

**End of README**
