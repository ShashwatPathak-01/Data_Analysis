# 🛒 Online Sales Data Analysis

This repository contains a Jupyter Notebook that explores and analyzes an online sales dataset using a combination of **Pandas** for data manipulation and **SQLite** for executing SQL queries on the data.

---

## 📁 Files

- `Online_Sales.ipynb` – Main notebook performing data cleaning, SQL integration, and analytical queries.
- `online_sales_dataset.csv` – CSV file with transactional sales data. (You must place this in the same directory for the notebook to run.)

---

## 🧰 Tools & Libraries Used

- Python 3.x
- Pandas
- Matplotlib (imported, but not used in current notebook)
- SQLite (`sqlite3` module)

---

## 📊 Key Analyses Performed

- Checked for and removed null values (replaced with `0` in `ShippingCost`)
- Converted invoice dates to datetime format
- Loaded data into an SQLite in-memory database
- Executed SQL queries:
  - Total sales value = `SUM(UnitPrice * Quantity)`
  - Extracted month from each invoice date
  - Grouped data by month and customer
  - Counted total number of customers (`44,804`)

---

## 🚀 How to Run

1. Clone this repo
2. Make sure `online_sales_dataset.csv` is in the same directory
3. Open the notebook in JupyterLab or VS Code
4. Run all cells step-by-step

---

## 📌 Notes

- The notebook currently uses an **in-memory database** (`:memory:`). Data is not saved between runs.
- Visualization (`matplotlib`) is imported but not utilized—this could be a good next step!

---

## 🧠 Potential Improvements

- Add data visualizations (sales trends, customer distribution, etc.)
- Normalize country data for better grouping
- Build an interactive dashboard using Plotly or Streamlit

---

## 📬 Contact

Feel free to open issues or contribute improvements. Happy analyzing!

