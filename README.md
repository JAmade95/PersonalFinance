# PersonalFinanceAnalysis 

This Jupyter Notebook project aims to provide insights into your spending habits by analyzing transaction data from a  Kaggle dataset named "personal_transactions.csv". The code generates static visualizations to illuminate spending patterns.

**Key Visualizations**

* **Pie Chart:**  Illustrates the percentage breakdown of your spending across various categories (e.g., Groceries, Entertainment, Shopping). This helps identify major areas of expenditure.

* **Line Plot:** Depicts how your aggregated spending fluctuates over time (monthly basis). This visualization can reveal seasonal trends or changes in your spending behavior.

**Dataset Requirements**

* **CSV File:** "personal_transactions.csv" from Kaggle 
* **Essential Columns:**
    * "Date" (dates in a standard format)
    * "Description"
    * "Amount" (transaction amounts)
    * "Transaction Type" (e.g., "debit" for expenses, "credit" for income)
    * "Category" (spending categories)
    * "Account Name"

**Tools**

* **Python 3:**  Core programming language.
* **pandas:**  Powerful library for data manipulation and analysis.
* **matplotlib:**  Essential library for creating  visualizations.

**Prerequisites**

Ensure you have pandas and matplotlib installed (`pip install pandas matplotlib`).

**Instructions**

1. **Open Notebook:** Launch the 'PersonalFinanceAnalysis.ipynb'  file in Jupyter Notebook.
2. **Run Cells:** Execute all cells within the notebook. 
3. **Interpret Results:**  Examine the pie chart and line plot to decipher insights about your spending.



# PersonalFinanceAnalysisInteractive

Building upon the 'PersonalFinanceAnalysis' project, this Jupyter Notebook introduces interactive elements for dynamic filtering of your transaction data.  The core purpose remains analyzing spending patterns, with this version providing more focused exploration on an account-by-account basis.

**Interactive Features**

* **Account Dropdown:** Enables the selection of a specific account (e.g., Platinum Card, Checking). Visualizations automatically update to reflect data from the chosen account.

**Visualizations**

The notebook generates the same visualizations as 'PersonalFinanceAnalysis': pie charts for category distribution and line plots for spending trends over time.  The key difference is the interactivity, allowing you to compare how these patterns differ across your accounts.

**Tools**

* **Python 3**
* **pandas**
* **matplotlib**
* **ipywidgets:** Library for creating interactive elements (the account dropdown).

**Prerequisites**

Ensure you have pandas, matplotlib, and ipywidgets installed (`pip install pandas matplotlib ipywidgets`).

**Instructions**

1. **Open Notebook:** Launch the 'PersonalFinanceAnalysisInteractive.ipynb' file in Jupyter Notebook.
2. **Run Cells:** Execute all cells.
3. **Select Account:**  Use the dropdown to choose an account.
4. **Analyze:** Observe how pie charts and line plots change to reflect account-specific spending.  

**Notes**

* **Dataset:**  This project uses the same dataset as 'PersonalFinanceAnalysis'.
