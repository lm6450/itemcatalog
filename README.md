# Item Catalog Project
Building a catalog app that allows the user to create categories (restaurants) and edit items (menu items) whn logging in. User can only edit and add items to their own categories. 

## Technologies used
1. FB login API
2. DB-API Python
3. Vagrant
4. Git

## Project Requirements
"You will develop an application that provides a list of items within a variety of categories as well as provide a user registration and authentication system. Registered users will have the ability to post, edit and delete their own items."


## System setup and how to view this project
Udacity's Linux-based virtual machine (VM)
1. Download [Vagrant](https://www.vagrantup.com/)
2. Download [Virtual Box](https://www.virtualbox.org/)

#### Run these commands:
1. ```vagrant up``` 
2. ```vagrant ssh``` 
3. ```cd /vagrant``` 
4. ```python database_setup.py``` 
5. ```python lotsofmenus.py``` 
6. ```python project.py``` 
7. Go to http://localhost:5000 on browser
8. Log in using Facebook
	NOTE: DO NO USE GOOGLE SIGN IN, it has been discontinued and will not work.
9. Create a category (restaurant) and edit, read, and delete the items (menu items)