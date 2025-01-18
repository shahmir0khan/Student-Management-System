# Student Management System

## Overview
This project is a comprehensive **Student Management System** designed to efficiently manage student records, including personal details, academic performance, and course enrollments. The system streamlines administrative tasks, enhances data accuracy, and provides easy access to student information.

---

## Technologies Used

### Frontend:
- **HTML, CSS, JavaScript**: For building the user interface and providing interactivity.

### Backend:
- **Flask**: A Python-based micro-framework for handling data processing and management.

### Database:
- **MySQL (phpMyAdmin)**: For storing and managing system data.

---

## Features

### Login Page
- Secure login system for Admin, Student, and Faculty.
- CAPTCHA verification using Google Secret and Site keys to prevent bots.

### Admin Panel Features
1. **Home Page**: Welcome page.
2. **Student Management**:
   - Full CRUD (Create, Read, Update, Delete) operations for student records.
3. **Faculty Management**:
   - Full CRUD operations for faculty records.
4. **Admin Management**:
   - Ability to register new admins and perform CRUD operations on admin records.
5. **Course Management**:
   - Add new courses.
   - Full CRUD operations on courses.
6. **Course Assignment**:
   - Assign courses to faculty members.
7. **Registration Control**:
   - Open/close course registration periods.
8. **Semester Management**:
   - Select the current academic semester.

### Student Panel Features
1. **Home Page**: Welcome page.
2. **Profile Management**: View personal profile details.
3. **Course Registration**:
   - Register for available courses within the allowed registration period.
4. **Registered Courses**:
   - View, drop, and manage enrolled courses.
5. **Attendance**:
   - View attendance records for all registered courses.
6. **Marks**:
   - View marks in enrolled courses.
7. **Feedback**:
   - Provide feedback for enrolled courses.
8. **Fee Details**:
   - View semester-wise fee details based on enrolled courses.
9. **Transcript**:
   - Generate academic transcripts and view grades and GPA for past semesters.

### Faculty Panel Features
1. **Home Page**: Welcome page.
2. **Profile Management**: View personal profile details.
3. **Attendance Management**:
   - Manage and update attendance records for courses they teach.
4. **Marks Upload**:
   - Enter and update marks for students in assigned courses.
5. **Feedback**:
   - View feedback provided by students for their courses.

---

## Installation

### Prerequisites
- Python (3.8 or later)
- Flask
- MySQL (phpMyAdmin)
- Google reCAPTCHA keys (Secret Key and Site Key)

### Steps to Install
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd student-management-system
   ```
3. Install required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Set up the MySQL database:
   - Import the `database.sql` file into phpMyAdmin.
   - Update the database credentials in the `config.py` file.
5. Run the Flask server:
   ```bash
   python app.py
   ```
6. Open the application in your browser at:
   ```
   http://127.0.0.1:5000/
   ```

---

## Usage
1. **Login**: Use the login credentials based on your role (Admin, Student, or Faculty).
2. **Explore Features**: Navigate through the respective panels to access features tailored for your role.

---

## Folder Structure
```
student-management-system/
├── static/                 # CSS, JS, and image files
├── templates/              # HTML templates
├── app.py                  # Main application file
├── config.py               # Configuration file for database and app settings
├── requirements.txt        # Python dependencies
├── database.sql            # SQL file for database setup
└── README.md               # Project documentation
```

---



---

## Contributors
- *SHAHMIR AHMED KHAN* - Developer


---

## Feedback
If you have any suggestions or issues, feel free to raise an issue in the repository or contact us at *shahmirahmedkhan84@gmail.com*.

---

Happy Coding! 🚀
