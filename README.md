# Intro to Django

## Django Snacks

Lab: 26 - Intro to Django

*Author: Natalie Sinner and Harry Potter*

----

## Description
The first words you see on the Django website are

Django makes it easier to build better Web apps more quickly and with less code.

The next quote you’ll see is

The web framework for perfectionists with deadlines.

In this class we’ll build out a small, but functional, multi page web site using Django.

We’ll get a feel for the “Django Way” and see the dramatic performance gains you can get with a mature, robust framework.

#### Feature Tasks and Requirements

Create web site in Django with 2 pages
home page
about page
create views/urls/templates as needed for home and about pages
use ancestor template to contain navigation elements
Should be built the “Django way” aka match the structure of in-class demo

---

### Getting Started
Clone this repository to your local machine.

```
$ git clone [https://github.com/nsinner1/django-snacks]
```

### To run the program from VS Code:
Select ```File``` -> ```Open``` -> ```django-snacks```

Next navigate to the location you cloned the Repository.

Double click on the ```django-snacks``` directory.

Then select and open ```django_snacks_project```

### To run in browser:
Locate directory in terminal

Activate virtual environment:

```
poetry init 
poetry shell
```
Once in virtual environment, run command:

```
python manage.py runserver
```

Once server is running, copy and paste URL: http://127.0.0.1:8000/

---

### Change Log
***[The change log will list any changes made to the code base. This includes any changes from TA/Instructor feedback]***  
1.3: *Completed lab 26* - 22 Aug 2020  
1.2: *Set up server and verified links are correct between each page* - 22 Aug 2020  
1.1: *Set up scaffolding* - 22 Aug 2020  


------------------------------
For more information on Markdown: https://www.markdownguide.org/cheat-sheet