# address-book
Create an app which have stack Django Rest Api as Back and React as Front side. Just add contact from inputs in Django Rest interface and after show full list of contacts by React. 





1.Project's Title

Web application for save user contact by Django and after show full list of contacts by React.

2.Project Description

We save the user's data through Rest Inteface as Json format and then display all the saved data in one list by React.

3.How to Install and Run the Project

To start our project in local server:

need make clone repo from git https://github.com/MoriartyJam/saddress-book

pip install virtualenv

virtualenv venv -p python3.8

source venv/bin/activate

pip install -U -r requirements.txt

python manage.py makemigrations

python manage.py migrate

python manage.py runserver


4.How to Use the Project

On the http://127.0.0.1:8000/api/lead/ url, enter data in the form and click the Post button. After that we can see your data on http://127.0.0.1:8000/ page.

