# Lets Study Together

A simple web application implemented using Django framework allowing participants to create rooms in different topics to share lessons

## Prerequisites

- Python
- Django

## Setup Instructions

Follow these steps to clone the project, set up the environment, and start the Django server locally.

### Clone the Repository

```bash
 git clone https://github.com/AbdessamedSed/Lets-Study-Together.git
cd .\Lets-Study-Together\
```
### Create and Activate Virtual Environment
```bash
python -m venv env
source env/bin/activate   # On Windows use `env\Scripts\activate`
```
### Install Dependencies
```bash
pip install -r requirements.txt
```
### Apply Migrations
```bash
python manage.py migrate
```
### Start the Development Server
```bash
python manage.py runserver
```
### Accessing the Application
Once the server is running, open a web browser and go to:
```bash
http://127.0.0.1:8000/
```


