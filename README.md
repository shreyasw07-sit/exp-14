Data Wrangling and Formatting using Python (Pandas)
This repository contains the implementation of Experiment 14, focusing on essential data preprocessing and wrangling techniques. These operations are critical for preparing raw datasets for exploratory data analysis (EDA) and machine learning models.

👤 Student Information
Name: Shreyas Wani

PRN: 25070123131

Institute: Symbiosis Institute of Technology (SIT), Pune

🎯 Aim
To perform data wrangling operations including data binning, type conversion, text formatting, and data sorting using the Pandas library.

🛠️ Technologies Used
Language: Python

Library: Pandas, NumPy

Environment: Google Colab / Jupyter Notebook

📑 Key Features Implemented
1. Data Binning (Categorization)
Transforming continuous numerical data into discrete categories (bins) using pd.cut().

Price & Sales Binning: Categorizing products into 'Low', 'Medium', or 'High' based on their price and units sold.

Order Logistics: Segmenting delivery times into 'Fast', 'Normal', or 'Slow' and distances into 'Short', 'Medium', or 'Long'.

2. Data Formatting & Type Conversion
Ensuring data consistency and correct formatting for analysis.

Type Casting: Converting integer columns (like unit_sold or Distance_km) to float to allow for more precise mathematical operations.

String Manipulation: Standardizing text data by converting product names or categories to UPPERCASE.

Value Rounding: Using .round() to maintain precision in financial or numerical columns.

3. Data Sorting
Organizing datasets to identify trends and outliers.

Ascending/Descending Order: Sorting data frames by specific columns (like Price or Order_Value) to view the highest or lowest performing entries.

🚀 How to Run
1.Clone the repository:

Bash
git clone https://github.com/your-username/data-wrangling-pandas.git

2.Install dependencies:

Bash
pip install pandas numpy

3.Execution:
Run the notebook cells to see the transformation from a raw dictionary/DataFrame to a structured, binned, and formatted dataset.
