## Zawadiana

### Developed By
### [Gesare](https://github.com/Gesare)


## Description
This is a Django website that allows a user to post a project he/she has created and get it reviewed by his/her peers.A project can be rated based on 3 different Criteria Design,
Usability and Content
 
## Features for the users:

Users would like to:
* View posted projects and their details
* Post a project to be rated/reviewed
* Rate/ review other users' projects
* View projects overall score
* View my profile page



## Specifications
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Admin Authentication | **On demand** | Access Admin dashboard |
| User Authentication | **On demand, verify emails before proceeding** | Access Admin dashboard |
| Display all projects with ratings | **Home page** | Clickable links to open any live site |
| Display images of the site | **On  click** | All details should be viewed and ratings available|
| To add an image  | **Through Admin dashboard and homepage** | Click on add and upload respectively|
| To edit image  | **Through Admin dashboard** | Redirected to the  image form details and editing happens|
| To delete an image  | **Through Admin dashboard** | click on image object and confirm by delete button|
| To search  | **Enter text in search bar** | Users can search by name of project|
| View other users profiles  | **Click username on user stories navigation** | Users can view all projects posted by any user|
| Rattings on images | **Rate projects below respective** | Users can add comments on any image|


## Getting Started
### Clone the Repo
Run the following command on the terminal:
`git clone https://github.com/Gesare/Zawadiana.git && cd Zawad

### Activate virtual environment
Activate virtual environment using python3.6 as default handler
```bash
virtualenv -p /usr/bin/python3.6 venv && source venv/bin/activate
```

### Install dependancies
Install dependancies that will create an environment for the app to run
`pip3 install -r requirements.txt`

### Create the Database
```bash
psql
CREATE DATABASE Dbname;
```
### .env file
Create .env file and paste paste the following filling where appropriate:
```python
SECRET_KEY = '<Secret_key>'
DBNAME = '<Dbname>'
USER = '<Username>'
PASSWORD = '<password>'
DEBUG = True
```
### Run initial Migration
```bash
python3.6 manage.py makemigrations collection
python3.6 manage.py migrate
```

### Run the app
```bash
python3.6 manage.py runserver
```
Open terminal on `localhost:8000`

### Prerequisites

1. Ubuntu Software
2. Python3.6
3. [Postgres](https://www.postgresql.org/download/)
4. [python virtualenv](https://gist.github.com/Geoyi/d9fab4f609e9f75941946be45000632b)


## Running the tests

```bash
python3.8 manage.py test awwardapp

```


## Deploying to heroku
Refer to this guide: [deploying to heroku](https://simpleisbetterthancomplex.com/tutorial/2016/08/09/how-to-deploy-django-applications-on-heroku.html)

Set the configuration to production mode

## Live Demo

The web app can be accessed from the following link: 

## Built With
* Python
* Material design
* WhiteNoise
* JavaScript
* CSS
* Django
* PostgreSQL Database


### License
Copyright (c) [2020] [Projectsapp] Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE..

