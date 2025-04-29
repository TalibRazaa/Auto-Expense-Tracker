# Automated Expense Tracker

A Python-based expense tracking application that helps you manage and analyze your expenses efficiently.

## Features

- Add and categorize expenses
- View expense history
- Generate expense reports
- Data visualization
- Data persistence using SQLite

## Setup

1. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
python main.py
```

## Usage

1. Add expenses with categories and amounts
2. View your expense history
3. Generate reports to analyze your spending patterns
4. Visualize your expenses through charts and graphs

## Project Structure

- `main.py`: Main application entry point
- `database.py`: Database operations and schema
- `expense_manager.py`: Core expense management functionality
- `reports.py`: Report generation and visualization
- `utils.py`: Utility functions 