
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

![Screenshot (22)](https://user-images.githubusercontent.com/63557848/129084353-d973ef7c-c535-41d9-bd23-8ef927629d24.png)

### A quick look in the Admin Page:
![Screenshot (27)](https://user-images.githubusercontent.com/63557848/129084809-b6bfd362-332c-4229-9dec-2d825cd17a78.png)

### How to run the server:
![Screenshot (20)](https://user-images.githubusercontent.com/63557848/129085260-ee12020f-dfeb-4198-be38-a96ade23901f.png)

### Looks!(Page adjusts itself for any device(phone,Laptop, big screen,...)
![image](https://user-images.githubusercontent.com/63557848/129084983-13ae318c-d185-49cf-a049-5d520b342631.png)


@33#@$#!@@#
