# real-time-chat
💬 Django WebChat

A simple real-time web chat application built with Django, jQuery, and AJAX.
This project allows users to create or join chat rooms, send messages, and view live updates without refreshing the page.

🚀 Features

🗨️ Create and join chat rooms

⚡ Real-time message updates using AJAX

👤 User-based message tracking

🧩 Simple and clean UI built with HTML/CSS/jQuery

💾 Stores chat data in the Django database

🛠️ Tech Stack

Backend: Django (Python)

Frontend: HTML, CSS, JavaScript (jQuery + AJAX)

Database: SQLite (default Django setup)

📁 Project Structure
chatapp/
│
├── chat/
│   ├── migrations/
│   ├── templates/
│   │   ├── home.html
│   │   └── room.html
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── admin.py
│
├── chatapp/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   ├── wsgi.py
│   └── __init__.py
│
├── manage.py
└── README.md
