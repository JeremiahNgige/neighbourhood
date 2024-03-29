# Neighbourhood

    Ngige Brian

## Descrition

This is a neighborhood app where a user must signup first, be able to join a hood owned by the hood admin, and once you
join a hood, one can see businesses and posts in only that wood they belong to.  

## User Story  
  
* Sign in with the application to start using.
* Set up a profile about me and a general location and my neighborhood name.
* Find a list of different businesses in my neighborhood.
* Find Contact Information for the health department and Police authorities near my neighborhood.
* Create Posts that will be visible to everyone in my neighborhood.
* Change My neighborhood when I decide to move out.
* Only view details of a single neighborhood.
  
## Setup and Installation  

To get the project .......  
  
### Cloning the repository

    <https://github.com/JeremiahNgige/neighbourhood.git>

#### Navigate into the folder and install requirements  

cd HoodWatch

##### Install and activate Virtual  

    python3 -m venv virtual - source virtual/bin/activate  

##### Install Dependencies  

    pip install -r requirements.txt 

##### Setup Database  

SetUp your database User,Password, Host then make migrate  

    python manage.py makemigrations hood

 Now Migrate  

    python manage.py migrate 

##### Run the application  

python manage.py runserver

Open the application on your browser `127.0.0.1:8000`.  
  
## Technology used  
  
* [Python3.8](https://www.python.org/)  
* [Django 3.1.3](https://docs.djangoproject.com/en/2.2/)  
* [Heroku](https://heroku.com)  
  
## Known Bugs  

* There are no known bugs currently but pull requests are allowed incase you spot a bug  
  
## License

* licensed under the [MIT license](LICENSE)  
* Copyright (c) 2020 **Jeremiah Ngige**
