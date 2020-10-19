# MarineLitter stakeholder Mapping

## Database is : MySQL

Install Mysql
Create a database

## Installing Django

1. Clone the project from github
2. `cd` into the outer marineLitter folder
3. Create a new virtual environment for your project using `python3 -m venv env`
4. Activate the env using `source env/bin/activate` (Linux/MacOs) || `env\Scripts\activate` (Windows)
5. Run `pip install -r requirements.txt` to install the projects requirements
6. Go to settings.py change the database name and password to the one you created when setting up Mysql
7. Run python manage.py makemigrations to make migrations to database
8. Run python manage.py migrate
9. Run python manage.py runserver to start the server
10. You should see

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
