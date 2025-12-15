# 🎓 Student Management System

A **role-based Student Management System** developed using **Python** and **MySQL**.  
This project helps institutes manage student records securely and efficiently.

---

## 📌 Project Overview

The system provides **two types of users**:

### 👤 Admin
- Manages student records
- Performs CRUD operations
- Searches and filters students
- Views analytics and insights

### 👨‍🎓 Student
- Logs in using Student ID
- Views personal details only (read-only access)

---

## 🚀 Key Features

### Admin Features
- Admin authentication
- Add new students
- Update student information
- Search students by name
- Search students by course
- Filter students by age range
- Analytics:
  - Total number of students
  - Students per course
  - Average age
  - Most popular course

### Student Features
- Secure login using student ID
- View own profile details
- No permission to modify data

---

## 🛠️ Technologies Used

- **Python**
- **MySQL**
- **mysql-connector-python**
- **python-dotenv**
- **Git & GitHub**

---

## 🗂️ Project Structure

student-project/
│
├── main.py
├── db_connection.py
├── student_crud.py
├── create_db2.py
├── create_tables.py
├── requirements.txt
│
├── auth/
│ ├── admin_auth.py
│ └── student_auth.py
│
├── utils/
│ ├── input_helpers.py
│ └── validators.py
│
└── .env (ignored for security)

---

## 🔐 Security Practices

- Database credentials are stored in `.env`
- `.env` is excluded using `.gitignore`
- Role-based access control (Admin & Student)
- Input validation to prevent runtime errors

---

## ▶️ How to Run the Project

1. Install dependencies:
   pip install -r requirements.txt
2. Create database and tables:
    python create_db2.py
    python create_tables.py
3. Run the application:
    python main.py

📊 Analytics & Insights

The project uses SQL aggregation functions to provide:

Student count

Course popularity

Age statistics


🔮 Future Enhancements

Password hashing

Database-based authentication

Logging and audit tracking

Web version using Flask or FastAPI



✅ Conclusion

This project demonstrates a structured backend application with:

Authentication

Role-based access

Database integration

Analytics

Clean modular design

It is suitable for backend development learning and interviews.
