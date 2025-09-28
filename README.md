# Expense Tracker Project

A simple command-line Python app to record daily expenses, save them into a CSV file, and view summaries.  
This is a beginner-friendly project written in Python and designed to run in Google Colab or any standard Python environment.

## Features
- Add expenses with date, category, amount, and optional notes
- Save data automatically to `expenses.csv`
- View total spent
- View totals by category
- View totals by month
- Simple text-based menu for navigation

## Example Usage
Menu:

1. Add expense
2. View summary
q. Quit


**Sample Output:**
========================
EXPENSE SUMMARY
Total: 1033.00

By Category:

rent 1015.00

coffee 8.00

By Month:

2025-08 500.00

2025-09 533.00


## How to Run
1. Clone or download this repository:
   ```bash
   git clone https://github.com/<diarbegolli>/expense-tracker-project.git
   cd expense-tracker-project
Run the program in Google Colab or locally with Python:


python expense_tracker.py
Follow the on-screen menu to add expenses or view summaries.

File Structure
expense_tracker.py — main project code

expenses.csv — CSV file where expenses are stored

README.md — project documentation

Future Improvements
Add data visualization (bar/pie charts for categories and months)

Integration with Google Drive for saving CSVs

Input validation for categories

Export summaries to PDF or Excel
