# Description
Blogging is one the most important task for any individual who wants to keep everyone informed of his/her updates regarding any incident(s). Bloggers is a Flask-based web appplication that lets user to post blogs regarding anything that he/she likes. 

# Features
1. Users can create new posts
2. Users can update their posts according to their wish
3. Users can delete their posts
4. Users can upload their display picture
5. User validation
6. Users can change their password
7. Email confirmation for password change

# Installation
* Fork this repository and clone it
* Create a file named ".env" in the parent folder
* Include these information in the file:

    SECRET_KEY = (YOUR PERSONAL SECRET KEY)
    SQLALCHEMY_DATABASE_URI = (YOUR SQLLITE URI)
    MAIL_SERVER = 'smtp.googlemail.com'
    MAIL_PORT = 587
    MAIL_USE_TLS = True
    MAIL_USERNAME = (YOUR GMAIL USERNAME)
    MAIL_PASSWORD = (YOUR GMAIL PASSWORD)

* Run the file named "run.py"
```bash
python3 run.py
```