# 💰 Personal Finance Tracker (Python CLI)

A clean and simple command-line tool to manage your income and expenses — built to make learning Python fun and practical.  
This is the **refined version** with a smoother UI, better structure, and more features.

---

## 🚀 Features

- 🟢 Add **Income** and **Expense** entries with category & description  
- 📜 View all transactions or just the 10 most recent ones  
- 📊 Get **category-based** and **monthly summaries**  
- 🗑️ Delete transactions easily using short IDs  
- 💾 Automatic CSV backup on exit  
- 📤 Export all data to JSON  
- 🎨 Clean, colorized interface using `colorama` (optional)

---

## 🧩 Folder Structure

📁 Personal-Finance-Tracker/
 ┣ 📜 Personal_Finance_Tracker_refined.py   ← main program
 ┣ 📁 data/
 ┃ ┣ 📜 transactions.csv                   ← main data file (auto-created)
 ┃ ┣ 📜 transactions_backup.csv             ← backup file (auto-created)
 ┃ ┗ 📜 transactions_export.json            ← optional export file
 ┗ 📜 README.md

---

## 🛠 Requirements

- Python 3.7 or above  
- Optional package for colored output:
  ```bash
  pip install colorama
  ```

---

## ▶️ How to Run

1. Clone or download this repository  
2. (Optional) Install colorama:
   ```bash
   pip install colorama
   ```
3. Run the program:
   ```bash
   python Personal_Finance_Tracker_refined.py
   ```
4. A folder named `data` will be created automatically to store all transaction files.

---

## 📈 Example CLI Output

=== Personal Finance Tracker ===
Track your income and expenses — clean, simple, and local.

Total Income : ₹12,000.00
Total Expense: ₹7,200.00
Current Balance: ₹4,800.00

1. Add Income
2. Add Expense
3. View All Transactions
4. View Recent Transactions (10)
5. Summary by Category
6. Monthly Summary
7. Delete a Transaction
8. Export to JSON
9. Backup & Exit

---

## 🧠 Key Learning Highlights

- Practiced clean code structuring using classes and modular design  
- Worked with file handling and CSV persistence  
- Enhanced user experience with colorized CLI and validations  
- Added reporting and summary functionalities (data grouping by category and month)

---

## 👨‍💻 Author

**Hammad Khan**  
B.Tech IT @ NSUT Delhi  
📍 Exploring Python, DSA, and AI through hands-on projects.  

💬 *“Learning by building — one project at a time.”*

---

## 🌱 Future Improvements

- Add a small dashboard using **Streamlit** or **Tkinter**  
- Visualize monthly spending trends using **matplotlib**  
- Add cloud sync support for multi-device use  

---

## 🧾 License

This project is open-source under the MIT License — feel free to modify and build upon it.
