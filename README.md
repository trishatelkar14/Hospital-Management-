
# 🏥 Hospital Management System

A Django-based web application designed to help hospitals manage doctors, patients, appointments, and medical reports in a simple and efficient way.

---

## 🚀 Project Overview

This Hospital Management System enables hospital staff to:
- Manage doctor and patient records
- Schedule and manage appointments
- Upload and manage medical reports
- Perform soft deletes and restore deleted data
- Handle user authentication (signup/signin/profile management)

It is built with a clean and responsive interface to ensure ease of use.

---

## ⚡ Key Features

- ✅ User Authentication (Signup, Signin, Profile Update)
- ✅ CRUD Operations for Doctors, Patients, Appointments, Medical Reports
- ✅ Soft Delete with History Tracking & Restore Option
- ✅ Media Uploads for Doctor/Patient Images & Reports (PDFs, Images)
- ✅ Intuitive, Responsive UI with basic animations
- ✅ Admin Dashboard for management tasks

---

## 🛠️ Technologies Used

- Python & Django (Backend Web Framework)
- SQLite (Database)
- HTML / CSS / Bootstrap (Frontend Design)
- JavaScript (Minimal for interactivity)
- Git (Version Control)

---

## 🧱 How to Run Locally

1. Clone the repository:
    ```bash
    git clone https://github.com/YOUR_USERNAME/hospital-management.git
    cd hospital-management
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Apply database migrations:
    ```bash
    python manage.py migrate
    ```

4. Create superuser (optional for admin access):
    ```bash
    python manage.py createsuperuser
    ```

5. Run the development server:
    ```bash
    python manage.py runserver
    ```

6. Visit in browser 👉 `http://127.0.0.1:8000`

---

## 📂 Media Files

- Doctors, Patients, and Medical Reports are stored in the `media/` folder.

---

## 📄 License

MIT License – Feel free to use and modify this project.

---

## 🌟 Why This Project?

This system demonstrates a real-world full-stack application by handling:
- Data Management (Doctors, Patients, Reports)
- File Upload and Media Handling
- Soft Delete & History Restore (Good software practice)
- User Authentication
- Responsive Design for usability

---

🔗 Explore, contribute, and improve hospital management efficiency! 🚑
