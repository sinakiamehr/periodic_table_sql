# 🧪 Periodic Table CLI Project

This is a **command-line program** built for the [freeCodeCamp Relational Database Certification](https://www.freecodecamp.org/learn/relational-database/). It uses **PostgreSQL** and **Bash** to display chemical element data from a structured `periodic_table` database.

---

## 📁 Project Structure

    ```bash
    periodic_table/
    ├── element.sh           # Bash script to query element info
    ├── periodic_table.sql   # PostgreSQL dump file to restore the full database
    └── README.md            # Project documentation

---

## ✅ Features

- Accepts **atomic number**, **symbol**, or **name** as input
- Outputs information about the element (mass, symbol, type, melting/boiling points)
- Handles errors for invalid or missing input
- Connects to a normalized PostgreSQL database
- CLI-driven and scriptable

---

## 🧠 Example Usage

### Look up info using element's identifier:
  ```bash
  ./element.sh (atomic_number, element_symbol, element_name) 
