# Task_Master

Task_Master is a simple Task Management Web Application built using Flask, Python, HTML, CSS, and SQLite. It helps users manage their daily tasks efficiently by allowing them to add, update, and delete tasks.

---

## Features

- Add new tasks
- Update existing tasks
- Delete tasks
- Stores task creation date and time
- Simple and clean UI
- SQLite database integration using Flask-SQLAlchemy

---

## Tech Stack

- Python
- Flask
- HTML
- CSS
- SQLite
- Flask-SQLAlchemy

---

## Project Structure

```bash
Task_Master/
│
├── app.py
├── test.db
├── static/
│   └── css/
│       └── main.css
│
├── templates/
│   ├── base.html
│   ├── index.html
│   └── update.html
│
├── env/
├── requirements.txt
└── README.md
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/goyalmuskan2212/Task_Master.git
```

### Move to Project Folder

```bash
cd Task_Master
```

### Create Virtual Environment

```bash
python -m venv env
```

### Activate Virtual Environment

#### Windows

```bash
.\env\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

---

## Database

This project uses SQLite database (`test.db`) to store task information.

---

## Future Improvements

- User Authentication
- Task Priorities
- Deadline Notifications
- Responsive UI
- Dark Mode

---

## Author

Muskan Goyal
