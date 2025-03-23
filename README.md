# 🎓 Student Management System using Django

## 🚀 Project Overview
This **Student Management System** is built using **Django** and provides an **Admin (HOD) Panel** for managing students, staff, courses, subjects, attendance, and leave applications. Future enhancements will include **separate dashboards for staff and students**.

## 📌 Features
### 🔹 **HOD (Admin) Panel**
- 👨‍💼 **Manage Staff & Students** – Perform **CRUD operations**
- 📚 **Manage Courses & Subjects**
- 📊 **Track Attendance** – View student attendance records
- 📩 **Handle Leave Applications** – **Approve or reject** staff/student leave requests
- 💬 **Check Feedback** – View feedback from staff and students & send replies

### 🔹 **Future Enhancements** 🚀
- 🏫 **Separate Staff & Student Panels**
  - ✅ **Mark Attendance** 📝
  - ✅ **Apply for Leave** 🏖️
  - ✅ **Submit Feedback** 💬
  - ✅ **View Results & Reports** 📊

## 🛠️ Installation & Setup
```bash
# Clone the repository
git clone https://github.com/Ayush8757/student-management-system.git
cd student-management-system

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Create superuser
python manage.py createsuperuser

# Run the development server
python manage.py runserver
```

## 🖥️ Usage
- **Admin Login**: `http://127.0.0.1:8000/`
- **Admin Panel Dashboard**: `http://127.0.0.1:8000/admin_home/`
- **Manage staff, students, courses, subjects, attendance, and more!**


## 💡 Contributing
Feel free to **fork** this repository, submit issues, or contribute improvements! 🚀

## 📩 Contact
For any queries, reach out to **Ayush Kacholiya** at **ayushrkacholia@gmail.com**

---
🌟 **If you found this project useful, don't forget to ⭐ the repository!**

