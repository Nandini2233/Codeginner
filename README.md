# Codeginner

*Codeginner* is an interactive learning platform built with Django.  
It provides *animated Python lessons, a **dashboard* to track learning progress, and a built-in *code editor* for hands-on practice. The platform is designed to make coding more engaging and beginner-friendly.

---

## 🚀 Features

- 🎬 *Animated Lessons* – Learn Python through interactive and engaging animated content.
- 📝 *Admin Panel* – Admin can add, update, and manage Python lessons.
- 📊 *User Dashboard* – Each learner gets a dashboard showing their progress and course completion status.
- 💻 *Integrated Code Editor*  
  - Built-in code snippets that match lesson topics.  
  - A normal editor for experimenting with Python code.  
- 🔒 *Authentication System* – Secure user login, signup, and role-based access.

---

## 🛠 Tech Stack

- *Backend:* Django (Python)
- *Frontend:* HTML, CSS, JavaScript, Bootstrap
- *Database:* SQLite (development), can be configured for PostgreSQL/MySQL
- *Code Editor:* Integrated in the platform

---

## 📂 Project Structure

Codeginner/ │── codeginnerApp/       # Main Django app │── media/videos/        # Animated lessons and media files │── db.sqlite3           # Default database (SQLite) │── manage.py            # Django project manager

---

## ⚙ Installation & Setup

1. *Clone the Repository*
   ```bash
   git clone https://github.com/Nandini2233/Codeginner.git
   cd Codeginner

2. Create Virtual Environment

python -m venv env
source env/bin/activate   # On Windows: env\Scripts\activate


3. Install Dependencies

pip install -r requirements.txt


4. Apply Migrations

python manage.py migrate


5. Create Superuser (for Admin Panel)

python manage.py createsuperuser


6. Run Development Server

python manage.py runserver


7. Open in Browser → http://127.0.0.1:8000/




---

🎯 Usage

Learners:

Sign up / log in.

Watch animated Python lessons.

Track your progress via the dashboard.

Practice Python in the built-in code editor.


Admins:

Add and manage new lessons.

Upload animated videos.

Monitor learner progress.








