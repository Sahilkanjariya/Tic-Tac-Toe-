🎮 Tic Tac Toe Game (Django)
A simple and interactive Tic Tac Toe web application built using Django.
The game supports two players, includes round-based scoring, and uses Django sessions to track game progress. The interface is designed with HTML, CSS, JavaScript, and Bootstrap, making gameplay smooth and responsive.

📌 Project Description
This project implements the classic Tic Tac Toe game using Django. Two players can enter their names, play multiple rounds, and view real-time updates of wins, losses, and draws. The game logic checks for winning combinations after every move and updates the scoreboard accordingly. Sessions are used to store the game state, score history, and player information.
This project is beginner-friendly and a good example for learning Django basics such as views, templates, session handling, and URL routing.

🚀 Features
✔ Two-player Tic Tac Toe
✔ Real-time win/draw detection
✔ Session-based score tracking
✔ Next Round (keeps scores)
✔ Reset Game (clears board + scores)
✔ Responsive UI using Bootstrap
✔ Player name input system
✔ Clean and interactive design

🛠 Tech Stack
Backend: Django (Python)
Frontend: HTML, CSS, JavaScript, Bootstrap
Database: SQLite (default Django DB)
Editor (recommended): VS Code

📦 Requirements
Make sure you have:
Python 3.x
pip (Python package installer)
Django (you will install it during setup)

1. Clone the Repository
   git clone https://github.com/your-username/tic-tac-toe-django.git
   cd tic-tac-toe-django
2. Create a Virtual Environment
   python -m venv venv
   venv\Scripts\activate
3. Install Dependencies
   pip install -r requirements.txt
   pip install django
   python manage.py makemigrations
   python manage.py migrate
   python manage.py runserver

