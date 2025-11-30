# Student Management System (SDBMS)

A comprehensive GUI-based application designed to manage student data, academic records, and performance analysis. Built using Python and MySQL, this system streamlines administrative tasks and provides advanced analytical features like marks prediction and report card generation.

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![MySQL](https://img.shields.io/badge/MySQL-Database-orange?style=for-the-badge&logo=mysql)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-green?style=for-the-badge)

## 📋 Table of Contents
- [About the Project](#about-the-project)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Screenshots](#screenshots)
- [Installation & Setup](#installation--setup)
- [Directory Structure](#directory-structure)
- [Future Improvements](#future-improvements)
- [Author](#author)

## 📖 About the Project
This project was developed as a Computer Science Class 12 project. It aims to digitize the manual process of handling student records. Unlike standard management systems, this application integrates **Machine Learning (Linear Regression)** to predict future student performance based on past exam trends and visualizes data using dynamic graphs.

## ✨ Key Features

### 1. User Authentication & Security
* Secure **Login/Register** system.
* Password encryption using **SHA-256 Hashing**.
* SQL Database connection verification at startup.

### 2. Student Management (CRUD)
* **Add New Students**: Auto-increments roll numbers to prevent duplication.
* **Search**: Dynamic search by Name, Class, Roll No, etc.
* **Update & Delete**: Modify student details or remove records securely.
* **Display**: View all student records in a tabular format.

### 3. Examination Management
* **Assign Subjects**: Map specific subjects to students.
* **Marks Entry**: Input marks for different exam terms (Half Yearly, Final).
* **Data Validation**: Ensures marks are within valid ranges (0-100).

### 4. Analytics & Reporting (Advanced)
* **Performance Graphs**: Uses `Matplotlib` to plot bar charts comparing Half Yearly vs. Final Exam performance.
* **Marks Prediction**: Uses `Scikit-Learn` (Linear Regression) to predict future marks based on previous performance trends.
* **Report Card Generation**: Generates a downloadable **PDF Report Card** using `ReportLab`.

## 🛠 Tech Stack

* **Language:** Python
* **Database:** MySQL
* **GUI Framework:** Tkinter
* **Data Visualization:** Matplotlib, NumPy
* **Machine Learning:** Scikit-Learn (LinearRegression)
* **PDF Generation:** ReportLab
* **Image Handling:** Pillow (PIL)
* **Security:** Hashlib

## 📸 Screenshots

| Login Screen | Student Menu |
|:---:|:---:|
| ![Login](screenshots/login.png) | ![Menu](screenshots/student_menu.png) |

| Data Visualization | Performance Prediction |
|:---:|:---:|
| ![Graph](screenshots/graph.png) | ![Prediction](screenshots/prediction.png) |

| PDF Report Card |
|:---:|
| ![Report](screenshots/report_card.png) |

## ⚙️ Installation & Setup

### Prerequisites
* Python 3.x installed.
* MySQL Server installed and running.

### 1. Clone the Repository
```bash
git clone [https://github.com/your-username/student-management-system.git](https://github.com/your-username/student-management-system.git)
cd student-management-system
