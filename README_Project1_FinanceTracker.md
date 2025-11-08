
# 💰 Personal Finance Tracker (CLI - Python)

A command-line interface (CLI) tool to manage personal income and expenses. This beginner-friendly project helped me master core Python fundamentals, file I/O, and menu-driven programming.

---

## 🚀 Features

- ✅ Add Income  
- ✅ Add Expense  
- ✅ View Current Balance  
- ✅ View All Transactions  
- ✅ Delete a Transaction by ID  
- ✅ Persistent CSV-based storage

---

## 🧠 Concepts Used

- Python Basics (variables, loops, conditionals)
- File Handling (CSV)
- Lists and Dictionaries
- Menu-based CLI design
- Random ID generation for entries

---

## 🗃 File Structure

```
personal_finance_tracker/
├── main.py                 # Menu and all functionality in one script
├── PersonalFinance.csv     # Transaction data (auto-created)
├── Deleted.csv             # Stores deleted transactions
└── README.md               # Project documentation
```

---

## 🧪 How to Run

1. Make sure Python 3.x is installed on your system
2. Clone this repository or download the files
3. Run the script in terminal:

```bash
python main.py
```

4. Follow the menu prompts to add/view/delete transactions

---

## 💾 Sample Transaction Format (CSV)

Each record is stored as:

ID, Amount, Type, Description/Source  
12501, 1000, Income, Freelance job  
12503, 150, Expense, Dinner

---

## 📌 Example CLI Interaction

```
==== Personal Finance Tracker ====
1. Add Income
2. Add Expense
3. View Balance
4. View All Transactions
5. Delete a Transaction
6. Save and Exit

Enter your choice: 2
Enter Expense Amount: 150
Enter Category: Food
✅ Expense added successfully!

Enter your choice: 3
💰 Current Balance: ₹850
```

---

## 💡 Future Enhancements

- Add monthly reports / summaries
- Categorize spending with filters
- Plot graphs with matplotlib
- Save to JSON as well

---

## 👨‍💻 Author

Hammad Khan  
Aspiring AI Engineer | BTech IT @ NSUT Delhi  
Project 1 of my AI Learning Roadmap
