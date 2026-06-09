# Stock Portfolio Tracker

## Overview

The Stock Portfolio Tracker is a Python-based console application that helps users calculate the value of their stock investments using predefined stock prices.

Users can enter stock symbols and quantities, and the application automatically calculates the value of each holding as well as the total portfolio value. The project also includes optional export features that save portfolio information to TXT and CSV files.

This project demonstrates the use of dictionaries, user input handling, arithmetic calculations, file handling, and object-oriented programming principles.

---

## Features

### Portfolio Management

* Add multiple stocks to a portfolio
* Enter custom quantities for each stock
* Validate stock symbols and quantities

### Investment Calculation

* Calculate individual stock values
* Calculate total portfolio value
* Display a formatted portfolio summary

### Portfolio Analysis

* Total investment value
* Total shares owned
* Average price per share
* Largest portfolio holding

### Data Export

* Export portfolio data to CSV format
* Export portfolio summary to TXT format

---

## Available Stocks

The application uses a predefined stock price dictionary:

| Symbol | Price ($) |
| ------ | --------- |
| AAPL   | 180.50    |
| TSLA   | 250.75    |
| GOOGL  | 2780.25   |
| MSFT   | 425.30    |
| AMZN   | 3520.80   |
| NVDA   | 890.45    |

---

## Technologies Used

* Python 3
* Dictionaries
* Functions
* Classes and Objects
* Input/Output Operations
* Arithmetic Calculations
* File Handling

---

## Project Structure

stock-portfolio-tracker-python/

├── stock_portfolio_tracker.py

├── README.md

├── portfolio.csv (generated)

├── portfolio.txt (generated)

├── requirements.txt

└── .gitignore

---

## How to Run

### Clone Repository

```bash
git clone https://github.com/your-username/stock-portfolio-tracker-python.git
```

### Navigate to Project Folder

```bash
cd stock-portfolio-tracker-python
```

### Run Application

```bash
python stock_portfolio_tracker.py
```

---

## Example Usage

```text
STOCK PORTFOLIO TRACKER

Stock symbol: AAPL
Quantity: 10

Stock symbol: TSLA
Quantity: 5

Stock symbol: done
```

### Output

```text
PORTFOLIO SUMMARY

AAPL  10  $180.50  $1805.00
TSLA   5  $250.75  $1253.75

TOTAL INVESTMENT: $3058.75
```

---

## Learning Outcomes

This project helped in understanding:

* Dictionary-based data storage
* Portfolio value calculations
* User input validation
* File export functionality
* Object-oriented programming
* Data formatting and reporting

---

## Future Improvements

Possible enhancements include:

* Real-time stock price integration
* Portfolio performance tracking
* Profit/Loss calculations
* Database support
* Graphical user interface (GUI)
* Portfolio diversification analysis

---

## Author

**Shubham Singh Tomar**

Python Developer | Software Engineering Enthusiast

---

## License

This project is licensed under the MIT License.
