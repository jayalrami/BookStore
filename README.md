📚 Bookstore Management System (Python & Pandas)
📌 Project Overview

The Bookstore Management System is a Python-based project that manages book inventory and sales data using Pandas.
It allows loading datasets, exploring data, adding books, updating inventory, and analyzing sales.

This project demonstrates practical usage of:

Object-Oriented Programming (OOP)

Data handling with Pandas

CSV file operations

Basic data analytics

🛠️ Technologies Used

Python 🐍

Pandas 📊

NumPy 🔢

CSV Files 📁

📂 Project Structure
Bookstore-Management-System/
│
├── BookStore.ipynb        # Main Jupyter Notebook
├── inventory_10000.csv    # Inventory dataset
├── sales_10000.csv        # Sales dataset
├── README.md              # Project documentation

📥 Dataset Description
1️⃣ Inventory Dataset (inventory_10000.csv)

Contains information about books available in the store.

Example columns:

Book_ID

Title

Author

Genre

Price

Stock

2️⃣ Sales Dataset (sales_10000.csv)

Contains records of book sales.

Example columns:

Sale_ID

Book_ID

Quantity

Sale_Date

Revenue

🚀 Features
✅ Load Data

Load inventory and sales data from CSV files.

def load_data(self):
    try:
        self.inventory = pd.read_csv(self.inventory_file)
        print("Inventory loaded!")
    except Exception as e:
        print("Error:", e)

✅ Explore Dataset

View dataset structure and summary.

Head of dataset

Shape of data

Column names

Basic statistics

✅ Add Book to Inventory

Add a new book record into the inventory.

✅ Update Book Stock

Modify stock quantity for existing books.

✅ Sales Analysis

Perform analysis on sales data such as:

Total revenue

Best-selling books

Sales trends

▶️ How to Run the Project
Step 1: Install Required Libraries
pip install pandas numpy

Step 2: Run the Notebook

Open Jupyter Notebook and run:

jupyter notebook BookStore.ipynb

📊 Example Output

Inventory loaded successfully ✅

Sales dataset explored 📈

Books added and updated 📚

Sales insights generated 💰

🎯 Learning Outcomes

This project helps you understand:

OOP in Python

Real-world dataset handling

Data analysis using Pandas

File handling with CSV
