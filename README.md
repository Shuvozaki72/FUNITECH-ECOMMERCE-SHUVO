### Furnitouch- Furniture Online Shop
<hr>


<br>
Fist clone the repository using the following command

```bash
git clone https://github.com/0rakib0/Furnitouch-Ecommerce-Website.git
# After cloning, move into the directory having the project files using the change directory command
cd Furnitouch-Ecommerce-Website
```
Create a virtual environment where all the required python packages will be installed

```bash
# Use this on Windows
python -m venv env
# Use this on Linux and Mac
python3 -m venv env
```
Activate the virtual environment

```bash
# Windows
.\env\Scripts\activate
# Linux and Mac
source env/bin/activate
```
Install all the project Requirements
```bash
pip install -r requirements.txt
```
-Apply migrations and create your superuser (follow the prompts)
```bash
# apply migrations and create your database
python manage.py migrate

# Create a user with manage.py
python manage.py createsuperuser
```

Run the development server

```bash
# run django development server
python manage.py runserver
```



### Demo dotend 

###### SCR_KEY = 'secret key'
###### DEBUG_STATUS = True
###### ALLOWED_HOSTS='allow hosts'
###### DB_NAME = 'db name'
###### DB_USER = 'db user'
###### DB_PASSWORD = 'db password'
###### DB_HOST = 'db host'
###### DB_PORT = 'db port'
