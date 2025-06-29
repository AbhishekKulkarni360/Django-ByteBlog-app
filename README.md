# 📝 ByteBlog - A Django Blogging Platform

ByteBlog is a simple and powerful blog application built with Django. It allows users to create, edit, view, and delete blog posts. It’s designed as a lightweight personal blogging platform with clean UI and admin control.

---

## 🔗 GitHub Repository

> [github.com/AbhishekKulkarni360](https://github.com/AbhishekKulkarni360/Django-ByteBlog-app)

---


## 🚀 Features

- User authentication (Login, Logout, Register)
- Create, update, delete blog posts
- View post details and list
- Django admin integration
- Responsive and minimal UI

---

## 🏗️ Tech Stack

- Python 3.x
- Django 4.x+
- SQLite (default, can be changed to PostgreSQL/MySQL)
- Bootstrap 4/5 (optional, for UI styling)

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/AbhishekKulkarni360/Django-ByteBlog-app.git
cd Django-ByteBlog-app
```
### 2. Create & Activate Virtual Environment
```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies
   ```bash
   pip install django
   ```
### 4. Run Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```
### 5. Create Superuser (Admin)
```bash
python manage.py createsuperuser
```
### 6. Start the Development Server
```bash
python manage.py runserver
```
Now open http://127.0.0.1:8000 to see the app.
---
### 🧪 Testing
Run Django’s test suite:
```bash
python manage.py test
```
### 📁 Project Structure
```
ByteBlog/
├── migrations/
├── static/
├── templates/
│   ├── base.html
│   ├── post_list.html
│   ├── post_detail.html
│   └── ...
├── admin.py
├── models.py
├── views.py
├── urls.py
└── ...
```

### 🧑‍💻 Author

**Abhishek Kulkarni**  
GitHub: [@AbhishekKulkarni360](https://github.com/AbhishekKulkarni360)

### 📄 License

This project is licensed under the [MIT License](LICENSE).

### 💡 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
