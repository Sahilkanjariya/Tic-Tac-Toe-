# 🎮 Tic Tac Toe Game (Django)

A simple and interactive **Tic Tac Toe** web application built using **Django**.  
The game supports two players, includes round-based scoring, and uses Django sessions to track game progress.  
The interface is designed with **HTML, CSS, JavaScript, and Bootstrap**, making gameplay smooth and responsive.

---

## 📌 Project Description

This project implements the classic **Tic Tac Toe** game using Django.  
Two players can enter their names, play multiple rounds, and view real-time updates of wins, losses, and draws.

The game logic checks for winning combinations after every move and updates the scoreboard accordingly.  
Django sessions store:

- Game state  
- Score history  
- Player information  

This project is beginner-friendly and a great example for learning:

- Views  
- Templates  
- Session handling  
- URL routing  

---

## 🚀 Features

✔ Two-player Tic Tac Toe  
✔ Real-time win/draw detection  
✔ Session-based score tracking  
✔ **Next Round** (keeps scores)  
✔ **Reset Game** (clears board + scores)  
✔ Responsive UI using Bootstrap  
✔ Player name input system  
✔ Clean and interactive design  

---

## 🛠 Tech Stack

**Backend:** Django (Python)  
**Frontend:** HTML, CSS, JavaScript, Bootstrap  
**Database:** SQLite  
**Recommended Editor:** VS Code  

---

## 📦 Requirements

Make sure you have installed:

- Python 3.x  
- pip  
- Django  

---

## 🧩 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/tic-tac-toe-django.git
cd tic-tac-toe-django
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
pip install django
```

### 4. Run Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Start the Development Server
```bash
python manage.py runserver
```
