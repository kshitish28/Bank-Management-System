# 🏦 Bank Management System  

A **Java + SQL** based application for managing banking operations like user authentication, account creation, transactions, and balance inquiries.

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white) 
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)  
![Status](https://img.shields.io/badge/Status-Active-success)

---

## 📌 Features  

- **User Authentication** – Secure login for customers and bank staff.  
- **Account Management** – Create, update, and delete bank accounts.  
- **Deposit & Withdraw** – Perform transactions with database updates.  
- **Balance Inquiry** – Check available account balance in real-time.  
- **Transaction History** – View past transactions.  
- **Graphical UI** – Java **Swing** based interactive interface.  
- **Database Integration** – Uses **MySQL** for secure data storage.  

---

## 🛠️ Technologies Used  

| Technology  | Description  |
|-------------|--------------|
| **Java** | Core language used for logic & UI |
| **Swing & AWT** | Graphical User Interface (GUI) framework |
| **JDBC** | Database connectivity in Java |
| **MySQL** | SQL-based relational database for storage |
| **Git & GitHub** | Version control & collaboration |

---

## 📂 Project Structure  
```
Bank Management System/
│── src/
│   ├── bank/management/system/
│   │   ├── Login.java
│   │   ├── Account.java
│   │   ├── Transactions.java
│   │   ├── DatabaseConnection.java
│   │   ├── Deposit.java
│   │   ├── Withdraw.java
│   │   ├── BalanceCheck.java
│   │
│   ├── icon/
│   │   ├── atm2.png
│   │   ├── bankbg.png
│   │   ├── bank.png
│   │   ├── card.png
│   │   ├── provider.png
│── lib/
│── out/
│── .gitignore
│── Bank Management System.iml
│── README.md
```

---

## 🖼️ UI Icons  
The project includes **image assets** for better UI design. These icons are stored in `src/icon/`:

| 🏷 Image Name  | 🎯 Usage |
|--------------|--------|
| **atm2.png** | ATM-related UI elements |
| **bankbg.png** | Background for the banking system |
| **bank.png** | Bank logo/icon |
| **card.png** | Card-related operations (e.g., debit/credit card UI) |
| **provider.png** | Service provider-related transactions |

---

## 🚀 Installation & Setup  

### **1️⃣ Clone the Repository**  
```sh
git clone https://github.com/kshitish28/Bank-Management-System.git
cd Bank-Management-System
```

### **2️⃣ Set Up the Database**  
Install MySQL and create a database:
```sql
CREATE DATABASE bank_management;
```
Use the provided `bank_management.sql` file to import tables.

### **3️⃣ Configure Database Connection**  
Update `DatabaseConnection.java` with your database credentials:
```java
Connection con = DriverManager.getConnection("jdbc:mysql://localhost:3306/bank_management", "root", "password");
```

### **4️⃣ Compile and Run the Project**  
Compile Java files:
```sh
javac -d . src/bank/management/system/*.java
```
Run the main class:
```sh
java bank.management.system.Main
```

---

## 📸 Screenshots  
(Add relevant screenshots of login, dashboard, and transactions)
![Banking Dashboard](Screenshot (96).png)
---

## 🔥 Future Enhancements  

- 🚀 Admin Dashboard for Bank Managers  
- 🚀 Interest Calculation on savings accounts  
- 🚀 Multi-Bank Branch Support  
- 🚀 ATM Functionality Integration  

---

## 🤝 Contributing  
Pull requests are welcome! Open an issue for feature suggestions or bug reports.

---

## 📄 License  
This project is open-source and available under the MIT License.

---

## ⭐ Show some support!  
If you like this project, please ⭐ star the repository on GitHub! 😊
