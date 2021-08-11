
Django-MusicShop
====================

Django-MusicShop is an interactive sample website for music lovers who want to shop for an instrument. Website is built to work on any device as it adjusts the icons depending on the screen capacity and overall delivers quite an exciting vibe as the user scrolls down to find their desired instrument!




![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![Python](https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)
	![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)

# PyShop Django Project
### Summary
This is a website that displays different musical instruments, and demonstrates varios prices and icons via an engaging template writen in HTMl alongside an add to cart button to really deliver a feeling of a real online Music shop!
### Files
```

│
├───Products
│   │   admin.py  : File that builds the admin module, via which the admin can add and discount different products
|   | 	apps.py   : Delivers the name of the products via ProductsConfig
│   │   models.py : Contains two classes of Product and Offer, and models(name,price,stock,code, description,discount,...)
|   | 	tests.py  : Available for testint the run command
│   │   urls.py   : File with url patterns and folders
|   | 	views.py  : Displays texts on each page of the website
│   └───migrations
│   |         0001_initial.py : file containing Migration class and Models of the icons
│   |         0002_offer.py  : file that contains the models for the discount offer feature of the website 
│   │         __init__.py
│   │
│   └───templates
│           base.html : template file for the main page for the products
│           index.html : template file for each product card
├───pyshop
│       asgi.py : ASGI config for the project
│       settings.py : File for application runs(admin,auth,sessions, messages,..) and MiddleWare
│       urls.py : Makes it able to access urls through admin
│       wsgi.py  : wsgi application
│
├───venv
│       Lib : All site-packages, pip, Django infos,...
|        Scripts : Activation files
|	gitignore 
|	pyvenv.cfg
|
├───
|	manage.py : Python file that when run launches the web app
|	db.sqlite3 : SQLite database
|

```

### Instructions:
1. Run the following commands in the project's therminal to set up your database and model.

    - To make a new migration
        `python manage.py makemigration`
    - To run the pending Migrations
        `python manage.py migrate`

2. Run the following command in the programms therminal to run your web app.
    `python manage.py runserver`

3. Go to http://127.0.0.1:8000/products/

### Admin Panel:

![Screenshot (15)](https://user-images.githubusercontent.com/63557848/129075833-794a51ff-5e1d-4917-8453-b3df31141956.png)

### A quick look in the Admin Page:
![Screenshot (17)](https://user-images.githubusercontent.com/63557848/129076152-ec03c697-cac5-4ef2-b73b-d990282b8d4a.png)




