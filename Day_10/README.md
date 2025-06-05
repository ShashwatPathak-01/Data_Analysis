# 🛒 Online Sales SQL Analysis

This repository contains a Jupyter notebook that performs structured analysis on an online retail sales dataset using **SQLite** and **pandas**.

## 📂 Files Included
- `Sales.ipynb`: The main notebook that reads the dataset, stores it in an SQLite in-memory database, and performs SQL queries for insights.
- `online_sales_dataset.csv`: The source dataset used in the analysis. *(Note: not included in this repo for size/privacy reasons)*

## 🧰 Tools & Libraries Used
- Python 3.x
- pandas
- sqlite3
- matplotlib, seaborn (for optional visualization)

## 🔍 Key Analyses Performed
- Total sales revenue computation
- Total quantity of items sold
- Item-wise aggregation: quantity and revenue
- SQL-based querying using `sqlite3` and `pandas.read_sql_query`

## 💡 How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/ShashwatPathak-01/Data_Analysis.git
    cd Data_Analysis
    ```
2. Open `Sales.ipynb` using Jupyter Notebook or VS Code with Jupyter extension.
3. Ensure `online_sales_dataset.csv` is present in the working directory.
4. Run the notebook cells step-by-step.

## 📈 Future Enhancements
- Add time-based sales analysis
- Use indexes for faster SQL querying
- Integrate data cleaning and anomaly detection

## 📜 License
This project is licensed under the MIT License.

