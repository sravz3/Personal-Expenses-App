
## Usage

1. Run the Streamlit app from the command line:
   ```bash
   streamlit run main.py
   ```

2. Your default web browser will open, and you'll see the Personal Expenses App App interface.

3. View the list of available expenses categories. Add new categories if needed.

4. To record an expense, input date, select category and amount of expense incurred.

5. Click the "Submit Expense" button to save your expense record.

6. You can also import all your expense in csv format by clicking on "Download Data as CSV" button.


# 💰 Personal Expenses Tracker App with Streamlit & SQLite

This project showcases how to build a lightweight, database-driven web application for tracking personal expenses using **Streamlit** and **SQLite**. It's perfect for anyone who wants a quick and intuitive way to log, view, and manage personal finances—without relying on complex tools or third-party apps.

👉 [Read the full tutorial on Medium](https://medium.com/data-science/from-zero-to-app-building-a-database-driven-streamlit-app-with-python-4c3f64fa4770)

---

## 🚀 Features

- Interactive web UI built with Streamlit  
- Lightweight backend using SQLite  
- Add and manage custom expense categories  
- Log daily expenses with category and date  
- Download expenses data as a CSV file  
- Easily customizable for your own use cases  

---

## 📦 Installation

To set up the app locally, follow these steps:

1. **Clone the repository**
   ```bash
   git clone https://github.com/sravz3/expenses.git
   cd expenses
2. **Create and activate a virtual environment**, then install dependencies.
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt

## ▶️ Usage

To launch the app:

```bash
streamlit run main.py

Then open your browser to view the app (usually at http://localhost:8501).

---

## 🧭 App Functionality
- Expense Categories: View, add, and manage custom categories for expenses.
- Add Expense: Enter the date, category, and amount to record a new expense.
- Download as CSV: Export your full expense log as a CSV for offline analysis.

---

## 🛠️ Customization
- You can easily extend this app to:
- Include income tracking
- Add monthly summaries and visualizations
- Sync with cloud databases (PostgreSQL, etc.)
- Authenticate users for multi-user tracking



