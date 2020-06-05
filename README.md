# Deploy Django App to Heroku

# Usage
If you don't have git installed, follow this Tutorial and come back here.

1.Make a copy of your project or use a seperate git branch.

2. Make sure your virtual environment is activated.

3. Add your dependencies to requirements.txt by typing in the terminal,

4. pip freeze > requirements.txt
5. A dd this in settings.py
STATIC_ROOT = os.path.join(BASE_DIR, 'static')

#Make a Heroku account

1. Download Heroku CLI

2. Configure Django Heroku

# In your terminal, type in

1. git init
2. git add .
3. git commit -m "first commit"

# heroku

1. heroku login
2. heroku create app_name
3. git push heroku master
4. heroku open

heroku run python manage.py migrate
** PS: if Heroku isn't recognized as a command, please close your terminal and editor and then re-open it.

1.DEBUG = False in settings.py

If you make edits, then just type in the terminal,

# github
1. git add .
2. git commit -m "edit"
3. git push heroku master
