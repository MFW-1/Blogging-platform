📝 Django Blogging Website

A full-featured blogging platform built with Django, allowing users to create, edit, publish, and manage blog posts with authentication and an admin dashboard.

🚀 Features

🔐 User Authentication (Login / Register / Logout)

✍️ Create, Edit, Delete Blog Posts

📄 Rich Text Content Support

🏷️ Categories / Tags

💬 Comment System

📊 Admin Dashboard

📱 Responsive Design

🔎 Search Functionality

🗂️ Pagination

🖼️ Media Upload Support

🛠️ Built With

Python 3.x

Django

SQLite / PostgreSQL

HTML5

CSS3 / Bootstrap

JavaScript

📂 Project Structure
blog_project/
│
├── blog/               # Main blog app
├── users/              # Authentication app (if separate)
├── templates/
├── static/
├── media/
├── db.sqlite3
├── manage.py
└── requirements.txt
⚙️ Installation & Setup

Follow these steps to run the project locally:

1️⃣ Clone the Repository
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
2️⃣ Create Virtual Environment
python -m venv venv

Activate virtual environment:

Windows

venv\Scripts\activate

Mac/Linux

source venv/bin/activate
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Apply Migrations
python manage.py migrate
5️⃣ Create Superuser
python manage.py createsuperuser
6️⃣ Run Development Server
python manage.py runserver

Open in browser:

http://127.0.0.1:8000/
🔑 Environment Variables (If Used)

Create a .env file in the root directory and add:

SECRET_KEY=your_secret_key
DEBUG=True
ALLOWED_HOSTS=127.0.0.1,localhost
📸 Screenshots

Add screenshots of your homepage, dashboard, and blog detail page here.

🌍 Deployment

You can deploy this project on:

Heroku

Render

PythonAnywhere

AWS

DigitalOcean

📌 Future Improvements

Like/Dislike System

User Profiles

Email Notifications

Social Media Sharing

REST API using Django REST Framework

🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.

📄 License

This project is licensed under the MIT License.
