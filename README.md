# 📦 Inventory Management System – Java & SQL (MVC Architecture)

This project is a full-featured **Inventory Management System** developed as part of the Software Design and Development (SDD) module. It demonstrates solid software engineering principles, including **modular design**, **MVC architecture**, **data persistence**, and **real-time UI updates** for managing product inventory.

---

## 🚀 Features

### 🧮 Inventory Functionality
- Add, update, and delete product records
- Real-time stock level updates
- Batch operations for large datasets
- Search and filter functionality by product category or ID

### 💻 User Interface
- Java-based GUI using `Swing` / `JavaFX` (depending on your version)
- Responsive design with real-time form validation
- Separate admin and user views (if applicable)

### 🛠 Backend Logic
- Built with **Model-View-Controller (MVC)** design pattern
- Handles data logic separately from the user interface
- Robust error handling and input validation

### 🗃️ Database Integration
- Connected to an embedded **SQLite** or external **MySQL** database
- Uses SQL queries for CRUD operations
- Ensures data persistence and integrity

---

## 🧰 Tech Stack

| Layer          | Technology      |
|----------------|-----------------|
| Frontend       | Java Swing / JavaFX |
| Backend Logic  | Java (OOP + MVC) |
| Database       | MySQL / SQLite   |
| Testing        | JUnit (for validation methods) |

---

## 🔧 Setup Instructions

### Prerequisites:
- Java JDK 11+
- MySQL / SQLite setup
- IDE like IntelliJ or Eclipse

### Run the Project:

1. Clone the repository:
```bash
git clone https://github.com/yourusername/inventory-mvc-java.git
cd inventory-mvc-java
```
2. Import the project into your IDE.

3. Set up your database using the provided inventory_schema.sql script.

4. Update database credentials in DBConnection.java:

```bash
String url = "jdbc:mysql://localhost:3306/inventory_db";
String user = "root";
String password = "your_password";
```
5. Run Main.java.

## 🧠 Learning Outcomes
Applied real-world MVC design pattern in Java

Implemented persistent data handling with SQL databases

Designed responsive and modular GUIs

Learned how to manage datasets in real-time in desktop applications

## ⚙️ Future Improvements
Add login/authentication for admin and users

Implement role-based access control

Generate inventory reports in PDF format

Add barcode scanner integration for stock management

## 👤 Author
Losheni Meenakshi Sundaram
Student at University of London , Singapore Institute of Management
📫 Email: losheni.ms@gmail.com

## 📄 License
This project is for educational and academic use only.
