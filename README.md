April Anne O. Tandoc
CSIT327 - G5

# CampusConnect

CampusConnect is a Django web application built with a custom user model, secure authentication, role-based authorization, and a personalized dashboard styled with Bootstrap 5.

---

## 🚀 Quick Start Guide

### 1. Open Terminal & Activate Virtual Environment

**Windows (CMD/PowerShell):**
```cmd
cd campusconnect
.venv\Scripts\activate
```

**macOS / Linux:**
```bash
cd campusconnect
source .venv/bin/activate
```

---

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 3. Run Database Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

---

### 4. Create an Admin User (Optional)

To create an administrator account for access to `/admin` and the admin panel:

```bash
python manage.py createsuperuser
```

---

### 5. Start the Server

```bash
python manage.py runserver
```

Visit the app in your browser at **[http://127.0.0.1:8000/](http://127.0.0.1:8000/)**.

---

## 🛠️ Project Architecture & Routes

* **`/`** — Personalized User Dashboard
* **`/accounts/signup/`** — User Registration
* **`/accounts/login/`** — User Login
* **`/admin-panel/`** — Admin Dashboard (Admin users only)
* **`/admin/`** — Django Admin Interface
