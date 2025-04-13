# 🧪 NanoSQL: A Lightweight Educational DBMS

> **NanoSQL** is a lightweight JAVA-based mini DBMS that simulates core SQL operations for educational purposes.

## 📌 Introduction
Welcome to **NanoSQL** – my custom-built, lightweight DBMS engine designed to simulate how relational databases work under the hood. This project was born out of my curiosity to learn how SQL interpreters, data storage, and table schemas operate internally, without using any external libraries or full-fledged database systems.

NanoSQL mimics the core functionality of a simple SQL engine. It accepts SQL-like commands, parses them, and executes operations such as creating tables, inserting records, fetching results, and deleting data. All data is stored persistently using flat files.

---

## 🎯 Features
- 🔎 **Custom SQL Parser** – Parses and executes commands like `CREATE`, `INSERT`, `SELECT`, `DELETE`, and `DROP`.
- 💾 **Flat File Storage** – Stores data and schema definitions in plain text files.
- 🧱 **Basic Schema Support** – Supports user-defined table structures.
- 🧪 **Error Handling** – Graceful messaging for invalid or malformed queries.
- 🛠️ **Educational Design** – Code is clean, modular, and beginner-friendly for those learning DBMS concepts.

---

## 🧠 System Architecture
NanoSQL is built using pure Python and is structured into modules:
- **Parser Module**: Interprets SQL-like syntax and maps it to operations.
- **Execution Engine**: Carries out database actions based on parsed commands.
- **Storage Manager**: Reads/writes data and schema to local files.
- **Error Handler**: Provides informative feedback for invalid inputs.

---

## 📁 Folder Structure
```
├── data/                    # Stores all table data files
├── schema/                  # Stores table schema definitions
├── engine/                  # Core logic modules (parser, executor)
├── main.py                  # Entry point for the DBMS shell
├── utils.py                 # Helper functions
└── README.md
```

---

## 🚀 Getting Started
### Prerequisites
- Python 3.8+

### Installation & Usage
```bash
# Clone the repository
$ git clone https://github.com/yourusername/nanosql.git
$ cd nanosql

# Run the DBMS shell
$ python main.py
```

### Sample Commands
```
CREATE TABLE students (id, name, age);
INSERT INTO students VALUES (1, 'Alice', 22);
SELECT * FROM students;
DELETE FROM students WHERE id = 1;
DROP TABLE students;
```

---

## 🔮 Future Improvements
- ✅ Add `UPDATE` and `WHERE` clause support
- 📊 Implement indexing for faster lookups
- 🔐 Add basic user authentication for multi-user handling
- 🌐 Build a web interface with Streamlit or Flask

---

## 📜 License
This project is licensed under the **MIT License** – feel free to learn, fork, and improve!

---

## 🙌 Acknowledgments
- DBMS professors and textbooks
- Open-source DB engines like SQLite for design inspiration
- Python community for tools and documentation

---

## 👩‍💻 Author
**Aditya Akhouri**  
GitHub: [Adityaakhouri](https://github.com/Adityaakhouri)  
Email: [adityakhouri66@gmail.com](mailto:adityakhouri66@gmail.com@gmail.com)

