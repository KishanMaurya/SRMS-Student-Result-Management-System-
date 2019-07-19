# SRMS
Student Result Management System

[![Python Version](https://img.shields.io/badge/Python-3.7.1-brightgreen.svg)](https://python.org)
[![Django Version](https://img.shields.io/badge/Django-2.1-green.svg)](https://djangoproject.com)

Student Result Management System is my first Django project!! It's single user application where user can CRUD (Create, Update, Delete) student, subject, subject combination and result. Then students can view there result and download this as PDF file. This project is live now in https://srms-demo.herokuapp.com feel free to contribute this project and **if you like this project dont't forget to give a star** 

![Dashboard](Screenshots/dashboard.png "SRMS Dashboard")

## Running the Project Locally

First, clone the repository to your local machine:

```bash
git clone https://github.com/RiajulKashem/SRMS.git
```

Install the requirements:

```bash
pip install -r requirements.txt
```

Apply the migrations:

```bash
python manage.py migrate
```

Finally, run the development server:

```bash
python manage.py runserver
```

The project will be available at **127.0.0.1:8000**.

## License

The source code is released under the [MIT License](https://github.com/RiajulKashem/SRMS/blob/master/LICENSE).
