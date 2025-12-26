
# 🗂️ Task Tracker Application (Java + MySQL)

A **console-based Task Tracker application** developed using **Core Java** and **MySQL**, designed with **role-based access control**. This project supports multiple user roles such as **Super Admin, Tenant Admin, Team Lead, and Regular User**, allowing efficient task creation, assignment, and tracking.

---

## 📌 Features

- 🔐 **Role-Based Login System**
  - Super Admin
  - Tenant Admin
  - Team Lead
  - Regular User

- 📝 **Task Management**
  - Create, update, view, and manage tasks
  - Assign tasks to users
  - Track task status

- 🏢 **Tenant & User Management**
  - Multi-tenant support
  - User creation and role mapping

- 📜 **Audit Logs**
  - Tracks important actions for monitoring and accountability

- 🗄️ **Database Connectivity**
  - MySQL used for persistent storage
  - JDBC-based DB connection

---

## 🛠️ Technologies Used

- **Programming Language:** Java (Core Java)
- **Database:** MySQL
- **IDE:** Eclipse / VS Code
- **Build Type:** Console Application
- **Architecture:** DAO (Data Access Object) Pattern

---

## 📂 Project Structure

```

Task_Tracker/
│── Main.java
│
├── config/
│   └── DBConnection.java
│
├── dao/
│   ├── UserDAO.java
│   ├── TaskDAO.java
│   ├── TenantDAO.java
│   └── AuditLogDAO.java
│
├── model/
│   ├── User.java
│   ├── Task.java
│   ├── Tenant.java
│   └── AuditLog.java
│
└── service/
└── Business logic classes

````

---

## ⚙️ Setup & Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/task-tracker.git
````

### 2️⃣ Import Project

* Open **Eclipse / VS Code**
* Import as **Existing Java Project**

### 3️⃣ Configure Database

* Create a MySQL database
* Update DB credentials in:

```java
config/DBConnection.java
```

### 4️⃣ Run the Application

* Run `Main.java`
* Login using role-based credentials

---

## 🧪 Sample Login (Demo)

```
Login Email : lead@gcc.com
Password    : 123
Role        : Team Lead
```

---

## 🎯 Use Case

* Academic Mini / Final Year Project
* Java + DBMS Practice
* Role-Based Access Control Demonstration
* Console-based Enterprise Application

---

## 🚀 Future Enhancements

* Web-based UI (HTML, CSS, JS)
* REST API using Spring Boot
* JWT-based authentication
* Task priority & deadline alerts

---

## 👨‍💻 Author

**Jasim Shaik**
Electronics and Communication Engineering
Java | SQL | IoT | Networking

---

## 📄 License

This project is developed for **educational purposes**.


