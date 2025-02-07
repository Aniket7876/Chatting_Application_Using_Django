# Django Chat Application

A real-time chat application built using Django and Django Channels. This project supports user authentication, WebSocket communication for real-time messaging, and an intuitive user interface.

## Features

- **Real-Time Messaging**: Leveraging WebSockets for instant communication.
- **User Authentication**: Built-in login, signup, and logout functionality.
- **Persistent Chat History**: Messages are stored in a SQLite database.
- **Responsive UI**: A clean and user-friendly interface for seamless chatting.

## Requirements

- Python 3.8 or higher
- Django 5.0.6
- Django Channels
- SQLite (default for Django)
- WebSocket-compatible browser

## Installation

Follow the steps below to set up the project locally:

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/django-chat-app.git
cd django-chat-app
```

2. Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install Dependencies
```bash
pip install -r requirements.txt
```

4. Apply Migrations
```bash
python manage.py migrate
```

5. Create a Superuser
```bash
python manage.py createsuperuser
```

6. Run the Development Server
```bash
python manage.py runserver
```
