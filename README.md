# Neighborhood

#### Created By David Mathaga

## Description

Neighbourhood is a website that enables you to be in the know on what is going on in your neighbourhood.It showcases posts, alerts , and business contacts in your area

## Setup Requirements

- Git
- Web-browser or your choice
- Github
- Django 
- Pip
- Python 
- PostgreSQL


## Setup Installation

- Copy the github repository url
- Clone to your computer
- Open terminal and navigate to the directory of the project you just cloned to your computer
- Run the following command to start the server using virtual environment

```
python -m venv --without-pip env
```

- To activate the virtual environment

```
source env/bin/activate
```

```
curl https://bootstrap.pypa.io/get-pip.py | python
```

```
pip install -r requirements.txt
```

- To copy .env.example to .env

```
cp .env.example .env
```

- Edit the .env file and replace the values with your own Cloudinary credentials and database credentials

- Migrate data using command 
```
python manage.py makemigrations
python manage.py migrate
```

- Create Superuser
```
python manage.py createsuperuser
```

- To run the server

```
python manage.py runserver

```

- Open the browser and navigate to http://127.0.0.1:8000/ to see the application in action

## Technologies Used

The following languages have been used on this project:

- HTML
- CSS
- Bootstrap
- Python
- Django
- PostgreSQL

## Setup/Installation Requirements

- Live link to view the project <a target="_blank" href="https://thehooddavos.herokuapp.com/">Neighborhood</a>

