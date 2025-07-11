# Paytm UPI Analyzer 

This Python project helps you analyze your **Paytm UPI transaction statement** with detailed insights such as:

- 📂 Loading and cleaning your Paytm UPI Excel data
- 🧼 Handling missing values and preprocessing
- 📊 Performing EDA (Exploratory Data Analysis)
- 🧾 Categorizing expenses (Food, Travel, Shopping, etc.)
- 📅 Monthly transaction breakdown
- 💰 Calculating total money spent vs received
- 📈 Visual charts and graphs to represent insights

---

## Features

- Categorizes your expenses automatically using keyword mapping.
- Computes total money **spent** and **received**.
- Monthly transaction summary (amount and frequency).
- Pie charts and bar graphs for intuitive financial insights.
- Works entirely locally — **no data is stored** or shared.

---

## Sample Visuals

- Monthly Spending Bar Chart
- Category-wise Expense Pie Chart

---

## Input

- Upload your `Paytm_UPI_Statement.xlsx` file.
- The file must include columns like `Date`, `Amount`, and `Details`.

---

##  Getting Started

```bash
pip install pandas matplotlib seaborn openpyxl
python analyze_upi.py
