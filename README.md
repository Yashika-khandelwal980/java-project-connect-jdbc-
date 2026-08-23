# java-project-connect-jdbc-
# 🎓 Student Registration System (Java + MySQL)

A simple **Student Registration System** built using **Java Swing** and **MySQL**. This desktop application allows users to register student details, store them in a MySQL database, and manage records through an easy-to-use GUI.

## 🚀 Features

* Student Registration Form
* Save student data in MySQL
* Reset form fields
* Java Swing GUI
* JDBC Database Connectivity
* Simple and beginner-friendly project

## 🛠️ Tech Stack

* **Java** (JDK 17+)
* **Java Swing**
* **MySQL**
* **JDBC**
* **VS Code**

## 📁 Project Structure

```text
Java Project/
│── src/
│   ├── App.java
│   ├── connect.java
│   ├── studentRegistration.java
│   └── studentRegistration.class
│
│── lib/
│   └── mysql-connector-j-26.7.0.jar
│
├── bin/
├── README.md
```

## ⚙️ Database Setup

Create a MySQL database:

```sql
CREATE DATABASE student_db;
USE student_db;

CREATE TABLE students (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100),
    father_name VARCHAR(100),
    gender VARCHAR(20),
    email VARCHAR(100),
    phone VARCHAR(15),
    address VARCHAR(255)
);
```

## 🔗 JDBC Configuration

Update your `connect.java` file:

```java
String url = "jdbc:mysql://localhost:3306/student_db";
String user = "root";
String password = "your_password";
```

## ▶️ How to Run

1. Clone this repository

```bash
git clone https://github.com/your-username/student-registration-system.git
```

2. Open the project in **VS Code**

3. Add the MySQL JDBC JAR to the `lib` folder.

4. Compile and run:

```bash
javac -cp ".;lib/mysql-connector-j-26.7.0.jar" src/*.java
java -cp ".;lib/mysql-connector-j-26.7.0.jar;src" studentRegistration
```

## 📸 Screenshot
<img width="665" height="659" alt="Screenshot 2026-08-23 163011" src="https://github.com/user-attachments/assets/359a4d15-0862-4718-81e7-170e9dbdf69a" />

screenshots/home.png
```

## 👩‍💻 Author

**Yashika Khandelwal**

* B.Tech IT Student
* Learning Java, DSA & Full Stack Development

## ⭐ If you like this project

Give this repository a **Star** on GitHub!
