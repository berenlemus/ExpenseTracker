# ExpenseTracker

## Description
This Python application provides a simple interface for tracking expenses and visualizing expenditure patterns. Users can input their expenses under different categories and view a pie chart representing the distribution of expenses across categories. Additionally, the app allows users to save their expense report as an Excel file for further analysis.

## Features
- Add expenses under predefined categories.
- View a pie chart showing the distribution of expenses across categories.
- Save expense report as an Excel file for record-keeping and analysis.

## Requirements
- tkinter library (usually comes pre-installed with Python)
- matplotlib library (install using `pip install matplotlib`)
- pandas library (install using `pip install pandas`)

## Usage
1. Run the Python script (`expense_tracker.py`).
2. Enter the expense category and amount in the provided fields.
3. Click "Add Expense" to record the expense.
4. Click "Show Chart" to visualize expense distribution across categories.
5. Optionally, click "Save Report" to save the expense report as an Excel file.
6. Close the application by clicking the "Close" button.

## Important Notes
- Ensure that you have an active internet connection to install required dependencies (`matplotlib` and `pandas`) if not already installed.
- Make sure to input valid expense amounts, and ensure that both category and amount fields are filled before adding an expense.
- The application saves the expense report as an Excel file named `expense_report.xlsx` in the same directory as the script.
- If no expenses are recorded, the pie chart will not be displayed.
- Categories and corresponding expenses are stored in memory during the session. Closing the application will clear the data.

## Files
- `expense_tracker.py`: The main Python script.
- `README.md`: This file providing information about the application.

## Credits
- Inspired by: [YouTube tutorial](https://youtu.be/7w7ITwOgUAE?si=uSqkJzyLGj7IXyhd) on building a simple expense tracker.
