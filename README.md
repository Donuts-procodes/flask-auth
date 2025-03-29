# Flask Authentication System

This is a simple user authentication system built with Flask, Flask-Login, and Flask-SQLAlchemy. It provides user registration, login, logout, and a protected dashboard.

## 🚀 Features
- User registration with password hashing
- User login with session management
- Protected dashboard (accessible only after login)
- Logout functionality
- SQLite database integration

## 📌 Prerequisites
Ensure you have the following installed:
- Python 3
- `pip` (Python package manager)
- `virtualenv` (optional but recommended)

## 🔧 Installation

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/Donuts-procodes/flask-auth.git
cd flask-auth
```

### 2️⃣ Create a Virtual Environment (Optional but Recommended)
```sh
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate    # On Windows
```

### 3️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 4️⃣ Run the Application
```sh
python app.py
```
Or use Flask CLI:
```sh
flask run
```

The app will be available at: **http://127.0.0.1:5000/**

## 📁 Project Structure
```
flask-auth/
│── app.py               # Main Flask application
│── requirements.txt      # Dependencies
│── db.sqlite            # SQLite database (auto-created)
│── templates/           # HTML templates
│   ├── home.html
│   ├── login.html
│   ├── sign_up.html
│   ├── dashboard.html
│── static/              # CSS and other static files
│   ├── style.css
│── venv/                # Virtual environment (if created)
```

## 🔑 User Authentication Flow
1. **Register:** Create an account at `/register`
2. **Login:** Log in at `/login`
3. **Dashboard:** Access the protected route at `/dashboard` (requires login)
4. **Logout:** Log out using `/logout`

## 📜 License
This project is open-source. Feel free to use and modify it.

---
Made with ❤️ by Donuts-procodes

