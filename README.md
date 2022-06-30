# ShareNow

A simple Django web-app which enables users to share files.
A register and login system is implemented, using which users can create accounts and use them to upload files.  
The other users will then be able to see and download all the files uploaded by the users.

## Features:
- Has a login system for users to create accounts and login
- All filetypes are supported for upload
- The files shared by a user will be public and will be available for everyone to view and download
- A user can also delete a file uploaded by him/her.

## Tech Stack:
- Python
- Django
- HTML
- CSS
- Bootstrap
- JavaScript

## Steps to deploy:
- Create a python virtual environment:
    ```bash
    python -m venv env
    ```
    Activate it using the **Activate.ps1**/**activate.bat** on Windows, or **activate** on MAC/Linux.
- Go to the project folder, and install the requirements:
    ```bash
    pip install -r requirements.txt
    ```
- Run the following three commands to deploy:
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    python manage.py runserver
    ```
- A local instance of the web-app will be started on: http://127.0.0.1:8000/