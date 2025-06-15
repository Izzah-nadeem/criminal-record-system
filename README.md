# criminal-record-system

## 📖 Overview

This project is a **functional web-based Criminal Record Management System**, developed as part of an academic assignment. While this version is being shared to highlight the structure and interface only, the system itself includes a working backend and interactive features.

It is built using **Node.js**, **Express.js**, **EJS**, and **SQL Server**, following proper modularity and MVC-style separation.

---

## ✅ Core Functionalities 

The full version of this system includes:

- 🔐 **Login Authentication**  
  Secure login using backend validation.
  
  ![Screenshot (391)](https://github.com/user-attachments/assets/92c939bb-0038-4270-8e73-926c00a14145)
  
- 🔎 **Search Functionality**  
  Allows users to search records by:
  - Criminal ID
  - Victim ID

- ➕ **Add Criminal Records**  
  Form to add new criminal data to the database.

- 🗑️ **Delete Criminal Records**  
  Option to remove a criminal entry by ID.

- 📋 **Access Logs**  
  Logs key user actions (add/delete/search) for future auditing.



## 🧰 Tech Stack

- **Frontend**: HTML, CSS, JavaScript, EJS
- **Backend**: Node.js, Express.js
- **Database**: SQL Server (Schema files included)

---

## 📁 Project Structure
📁 public/ → Static assets (CSS, images, JS)
📄 index.js → Express server configuration
📄 criminal.ejs → Page template for displaying criminal data
📄 victim.ejs → Page template for displaying victim data
📄 project_main.sql → SQL script for table creation and schema setup
📄 prject_dcl.sql → SQL script for user and access permissions (DCL)
📄 README.md → Project documentation (this file)

