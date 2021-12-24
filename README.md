# To-Do Application

This is a simple Todo application built off Django (including the Django REST Framework for API CRUD operations) and React.

![todo](https://user-images.githubusercontent.com/63921263/147334320-84cc774b-079b-4d46-9dea-ca4ad30fcc93.gif)

## Technology Stack

**Frontend:** React  
**Backend:** Python/Django  
**Database:** SQLite3

## Setting-up the project

### Setting up the Backend

- Download and install Python 3.9
- Download and install Git.
- Fork the Repository.
- Clone the repository to your local machine `$ git clone https://github.com/<your-github-username>/to-do-application.git`
- Change directory to to-do-application/backend `$ cd to-do-application/backend`
- Install virtualenv `$ pip3 install virtualenv`
- Create a virtual environment `$ virtualenv env -p python3.9`  
- Activate the env: `$ source env/bin/activate` (for linux) `> ./env/Scripts/activate` (for Windows PowerShell)
- Install the requirements: `$ pip install -r requirements.txt`
- Make migrations `$ python manage.py makemigrations`
- Migrate the changes to the database `$ python manage.py migrate`
- Create admin `$ python manage.py createsuperuser`

### Setting Up the Frontend

- Download and install Node.js v15.8.0
- Change directory to to-do-application/frontend `$ cd to-do-application/frontend`
- Install dependencies `$ npm install`  

### Run the application

- You will need two terminals pointed to the frontend and backend directories to start the servers for this application.

  1. Run this command to start the backend server in the `backend` directory: `$ python manage.py runserver` (Make sure virtual environment is activated)
  2. Run this command to start the frontend server in the `frontend` directory: `$ npm start` (This will start the frontend server on the adddress [localhost:3000](http://localhost:3000))
