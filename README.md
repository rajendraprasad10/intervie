

<img width="930" alt="dj-1" src="https://user-images.githubusercontent.com/42211472/83881156-da085e00-a75d-11ea-9597-1555f45be17c.png">

<img width="922" alt="dj-2" src="https://user-images.githubusercontent.com/42211472/83881879-ed67f900-a75e-11ea-88b7-1a7da9c39dde.png">

<img width="926" alt="dj-3" src="https://user-images.githubusercontent.com/42211472/83881912-fe186f00-a75e-11ea-99ec-22120113034f.png">

<img width="785" alt="dj-4" src="https://user-images.githubusercontent.com/42211472/83881979-16888980-a75f-11ea-9b74-f1a04f4f8d4e.png">


<img width="782" alt="dj-5" src="https://user-images.githubusercontent.com/42211472/83882037-26a06900-a75f-11ea-8f7b-bd3d49f90812.png">

<img width="845" alt="dj-6" src="https://user-images.githubusercontent.com/42211472/83882086-3a4bcf80-a75f-11ea-851a-fddffe4b75b1.png">

<img width="785" alt="dj-7" src="https://user-images.githubusercontent.com/42211472/83882124-4899eb80-a75f-11ea-87af-6a4e9300c894.png">
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
