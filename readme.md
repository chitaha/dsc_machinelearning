# MarineLitter stakeholder Mapping

## Database is : MySQL

Install Mysql
Create a database

## Installing Django

Clone the project from github
cd into the outer marineLitter folder
Create a new virtual environment for your project using `python3 -m venv env`
Activate the env using `source env/bin/activate` (Linux/MacOs) || `env\Scripts\activate` (Windows)
Run `pip install -r requirements.txt` to install the projects requirements
Go to settings.py change the database name and password to the one you created when setting up Mysql
Run python manage.py makemigrations to make migrations to database
Run python manage.py migrate
Run python manage.py runserver to start the server
You should see

`Watching for file changes with StatReloader`
`Performing system checks...`

`System check identified no issues (0 silenced).`
`October 19, 2020 - 10:33:44`
`Django version 3.1, using settings 'marineLitter.settings'`
`Starting development server at http://127.0.0.1:8000/`
`Quit the server with CONTROL-C.`


''''
sudo apt-get install libmysqlclient-dev
pip3 install mysqlclient
''''