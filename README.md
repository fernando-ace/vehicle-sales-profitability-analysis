# 🚗 Vehicle Sales Profitability Analysis

This project analyzes vehicle sales data to uncover profitability metrics by vehicle make, body type, and other attributes.  
It includes a Jupyter/Colab notebook and a sample dataset for demonstration.  

The analysis and visualizations were originally performed on data stored in Snowflake, but this repository provides a self-contained demo using a **sample CSV file**.

---

## 📂 Contents

- `vehicle_sales_analysis.ipynb` — Interactive notebook with all analysis and visualizations.
- `sample_vehicle_sales.csv` — Sample dataset (random subset of original data).

---

## 📊 Analysis Includes

- Total and average profit by vehicle make  
- Average profit margin (%)  
- Most common body type  
- Median odometer reading  
- Unique makes & models sold  
- Average vehicle age at sale  
- Visualization of total profits by make

---

## 🚀 How to Run

### Option 1: Run on Google Colab (recommended)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fernando-ace/vehicle-sales-profitability-analysis/blob/main/vehicle_sales_profitability_analysis.ipynb)

1. Click the **Open In Colab** badge above to open the notebook in Google Colab.  
2. Upload the `sample_vehicle_sales.csv` file to the Colab environment (use the file upload button in Colab's file explorer).  
3. In the notebook, set the CSV path variable to:
    ```python
    csv_path = 'sample_vehicle_sales.csv'
    ```
4. Run all cells to reproduce the analysis and plots.

---

### Option 2: Run locally

1. Clone this repo:
    ```bash
    git clone https://github.com/fernando-ace/vehicle-sales-profitability-analysis.git
    cd vehicle-sales-profitability-analysis
    ```

2. Install dependencies:
    ```bash
    pip install pandas matplotlib seaborn
    ```

3. Open `vehicle_sales_analysis.ipynb` with Jupyter Notebook, JupyterLab, or VSCode.  
4. Set the CSV path variable in the notebook to:
    ```python
    csv_path = 'sample_vehicle_sales.csv'
    ```
5. Run all cells to reproduce the analysis.

---

## 📑 Notes

- The included `sample_vehicle_sales.csv` is a random subset of the original dataset.  
- The full dataset is not included due to size constraints and privacy.  
- If you have access to the full dataset, replace the sample file and update `csv_path` accordingly.

---

## ✨ License

This project is for educational and demonstration purposes.  
Feel free to fork and adapt!
