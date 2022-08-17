

## Background
# Policify
![alt text](https://github.com/D3troit98/huroku/blob/e1c835cdd316a07325bef37157bc618fabd20dd8/Screenshot%20(92).png?raw=true)

a website that enables users to create terms and conditions and privacy policies tailored to their particular line of work.

## Table of Contents

* [Background](#background)
* [About the Project](#about-the-project)
* [Objectives](#objectives-of-policify)
* [Features](#features)
* [Technology](#technology)
* [Deployment](#details-on-deployment)
* [Product Specification](#product-specification)
* [Contributors](#contributors)
* [Project Status](#project-status)
* [Details on Usage](#details-on-usage)
* [Collaboration](#collaboration)
* [Documentation](#documentation)
* [Acknowledgements](#acknowledgements)

## About the Project
* "Terms and Conditions" came into being as a result of the necessity to have a clear knowledge of the obligations, rights, and restrictions of parties to a contract or commercial transaction, as well as the usage guidelines and terms that were agreed to as being legally enforceable on both sides.

* This means that the existence of terms and conditions in every contractual relationship is a crucial consideration because it serves as the framework for how the business or contract functions.

# Problem Statement

Businesses spend thousands in legal fees for lack of agreement on core terms at the beginning of the contract. To avoid this, most business contract professionals to draft their terms and conditions, these professionals charge prohibitive fees which are unaffordable for such service. It has however become hard for businesses, especially small and medium scale, to get suitable terms and conditions and privacy policies for their businesses. 

Policify aims at reducing the hassles of individuals and Companies of  having to generate privacy policy and or t and c

## Objectives of Policify

* To provide a platform where various industry-specific terms and conditions and privacy policies can be generated.

* To help user's simplify every task needed to generate t&c and privacy policy.

* To absolve users of the huge cost of contracting professionals to draft the terms and conditions and privacy policies

## Features

# User(Unauthenticated)

* Visit the platform to view basic information about it

* View and Interact with the documentation

* Register to view more  details

* No access to use until registered

# User(Authenticated)

* Full access to the platform

* Allow users enter basic information

* Generate selected files with the right data and information

* Allow export, download, share and website embed

* Allow user save data and come back to download

## Technology 
* __Frontend__<br/>
      ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
      ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
      ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

* __Backend__<br/>
        ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
        ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)

* __Design__<br/>
        ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)


* __Version Control System__<br/>
        ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

* __Database__<br/>
      Postgres sql

## Details on deployment orunning on local machine

* Git clone
* create a virtual env
* Install all dependencies in requirements.txt
* Make a Postgresql database and give it the information found in settings.py file in the policifyproject directory on the database section.
* if your Postgresql database has different information from the settings. Then update the settings 
* cd into the source folder 
* run python manage.py makemigrations
* run Python manage.py migrate
* run python manage.py collectstatic
* run python manage.py runserver
* if having issue linking static files, then set DEBUG in settings.py in policifyProject to False then run python manage.py runserver --insecure or switch the DEBUG = False  to True and run python manage.py runserver

## Details on deployment orunning on Hosted machine

* Git clone
* create a virtual env
* Install all dependencies in requirements.txt
* Make a Postgresql databaseon heroku and connect it to the app by filling the database options in settings.py
* if you don't want to create a database. You can connect to the postgress database hosted already, provided its still online
* cd into the source folder 
* run python manage.py makemigrations to migrate to the database
* run Python manage.py migrate to host the data
* run python manage.py collectstatic
* run python manage.py runserver
* if having issue linking static files, then set DEBUG in settings.py in policifyProject to False then run python manage.py runserver --insecure or switch the DEBUG = False  to True and run python manage.py runserver

## Product Specification
* Mobile Phones
* Tablets
* Personal computers
## Contributors 

* Tijani Abiodun (Front-End Developer)
    * Track -  Fullstack
    * Github - https://github.com/Harbeytee

* Arthur Akalazu (Graphic Designer)
    * Track - Product Design
    * Github - https://github.com/aakalazu

* Duruaku Ebuka Micheal(Back-end Engineer)
    * Track - Fullstack
    * Github - https://github.com/D3troit98



## Documentation

Check here for a more detailed documentation on the progress and update of this project - 'soon'

## Acknowledgements

This project is acknowledged to The Zuri Team and the Collaborators of this project for their intense efforts in the completion of this project
