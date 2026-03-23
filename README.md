# User_Auth_App

A full-stack **Flask-based User Management System** with authentication, role-based access, and a modern SaaS-style UI.
This project demonstrates real-world features like login, registration, admin dashboard, profile management, and password reset.

---

## 📌 Features

* 🔐 User Authentication (Login / Register / Logout)
* 👤 User Profile Management
* 🛡️ Role-Based Access (Admin / User)
* 📊 Admin Dashboard (View / Edit / Delete Users)
* 📧 Email Verification System (UI Ready)
* 🔑 Password Reset Functionality
* 🎨 Modern SaaS UI (Custom CSS)
* ⚡ Session Management

---

## 🗂️ Project Structure

```
project/
│
├── app.py
├── database.db
│
├── static/
│   └── style.css
│
├── templates/
│   ├── base.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── profile.html
│   ├── admin.html
│   ├── verify.html
│   ├── reset_password.html
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

---

### 2️⃣ Create Virtual Environment (Recommended)

```
python -m venv venv
venv\Scripts\activate   # Windows
```

---

### 3️⃣ Install Dependencies

```
pip install flask
```

---

### 4️⃣ Run the Application

```
python app.py
```

---

### 5️⃣ Open in Browser

```
http://127.0.0.1:5000/
```

---

## 🧠 How It Works

### 🔐 Authentication Flow

```
Register → Login → Dashboard → Logout
```

* Passwords are stored securely
* Sessions manage user login state

---

### 👑 Admin Flow

```
Admin Login → Admin Dashboard → Manage Users
```

Admin can:

* View all users
* Edit user details
* Delete users

---

### 🔑 Password Reset Flow

```
Request Reset → Enter New Password → Login
```

---

## 🎨 UI Highlights

* Clean **SaaS-style design**
* Responsive card-based layout
* Sidebar admin dashboard
* Modern form inputs & buttons
* Smooth hover effects

---

## 📌 Technologies Used

* **Backend:** Flask (Python)
* **Frontend:** HTML, CSS (Custom SaaS UI)
* **Database:** SQLite
* **Templating:** Jinja2

---

## 🚀 Future Improvements

* ✅ Email verification (SMTP integration)
* ✅ Password hashing (bcrypt)
* ✅ Search & pagination in admin panel
* ✅ REST API integration
* ✅ JWT Authentication

---

## 🙌 Author

**Vishva**
Python Full Stack Developer Intern

---

## ⭐ Contribution

Feel free to fork this project and improve it. Pull requests are welcome!

---

## 📄 License

This project is open-source and available under the MIT License.

---
