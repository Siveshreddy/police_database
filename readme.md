# 🚓 Police Database Management System

![Java](https://img.shields.io/badge/Language-Java-orange) ![MySQL](https://img.shields.io/badge/Database-MySQL-blue) ![Status](https://img.shields.io/badge/Status-Active-brightgreen)

## 📄 Description
The **Police Database Management System** is a Java-based application designed to help police stations and law enforcement agencies manage criminal records, cases, and complaints efficiently. It replaces manual file keeping with a digital database system, allowing for quick retrieval of criminal history and case status updates.

## 🚀 Features
* **Add Criminal Records:** Store details like name, age, crime type, and photo.
* **Search Functionality:** fast search by Criminal ID, Name, or Crime Type.
* **Case Management:** Log new FIRs (First Information Reports) and track their status (Pending/Closed).
* **Update & Delete:** Modify existing records or remove resolved cases.
* **Secure Login:** Admin authentication for officers to prevent unauthorized access.

## 🛠️ Tech Stack
* **Programming Language:** Java (JDK 17+)
* **Database:** MySQL
* **Database Connectivity:** JDBC (Java Database Connectivity)
* **IDE:** VS Code / Eclipse / IntelliJ IDEA

## 📂 Project Structure
```text
police_database/
├── src/
│   ├── Main.java          // Entry point of the application
│   ├── DatabaseConn.java  // Handles MySQL connection
│   ├── Officer.java       // Officer login logic
│   ├── Criminal.java      // Criminal record management
│   └── CaseFile.java      // FIR and case tracking
├── lib/
│   └── mysql-connector.jar // JDBC Driver
├── database.sql           // SQL script to setup the tables
└── README.md
