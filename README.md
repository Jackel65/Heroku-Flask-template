# Heroku-Flask-template
Boilerplate for making flask apps and deploying them to Heroku


# steps inside powershell, make sure your cwd is the root project folder

1. create virtual environment

> virtualenv venv

> cd venv/Scripts

> .\activate

2. install the packages in the virutal environment 

> pip install flask gunicorn jinja2 etc.

3. update requirements.txt with pip 

pip freeze > requirements.txt

# SAVE requirements.txt WITH ANSI ENCODING OR IT WILL NOT WORK

4. use git 

> new-item .gitignore
> git init
> git add --all
> git commit -m "text to add to the commit"

5. deploy to heroku

> heroku login
> heroku create
> git remote -v
> git push heroku master


