# Online Retail Sales Analysis

Data cleaning, exploratory analysis, and an interactive sales dashboard for the **UCI Online Retail** dataset (UK-based online retailer, December 2010 – December 2011).

## Repository Structure

| File | Description |
| --- | --- |
| `online_retail_analysis.ipynb` | Complete notebook covering data cleaning, exploratory data analysis (EDA), and the interactive dashboard |
| `Online-Retail.xlsx` | Source dataset (not included in this repository) |

## Getting Started

### 1. Add the Dataset

Download the workbook from Moodle and save it as `Online-Retail.xlsx` in the same directory as `online_retail_analysis.ipynb`.

### 2. Install Dependencies

```bash
pip install pandas matplotlib plotly ipywidgets openpyxl nbformat

```

### 3. Run the Notebook

Open `online_retail_analysis.ipynb` in **Jupyter** or **VS Code**, then select **Kernel > Restart and Run All**.

## Interactive Dashboard

The final section of the notebook provides an interactive dashboard featuring:

* A **country dropdown**
* A **date range** selector
* A **UK** filter checkbox

> **Note:** Interactive `ipywidgets` controls require an active Jupyter or VS Code session and will not work in static HTML or PDF exports.
