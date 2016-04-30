# _Restaurants_

#### _A basic restaurant website_

### By _**Marika Allely and Torrence Stratton**_

## Description

#### This app was built as an exercise for Epicodus and is not meant to be replicated.  I'm keeping it here for my own records, and for nostalgia's sake.  Feel free to play with it, but be aware that it is not a complete project.

_This web app is designed to allow users to create shoe stores and shoe brands. The app was built using the micro-framework Silex, PHP, Twig, and Bootstrap._

_The goal of this code review is to show basic understanding and competency with many to many relationships in SQL, PHP, and the Silex micro-framework._


## Setup/Installation Requirements

1. Fork and clone this repository from [gitHub](https://github.com/MBAllely/restuarant_php).
2. In the terminal, navigate to the root directory of the project and run the command: __composer install__ .
3. In the terminal, start SQL by running the command: __mysql.server start__, and then run the command __mysql -uroot -proot__ .
4. In another terminal tab, start Apache by running the command __apachectl start__ .
5. In your browser, navigate to __localhost:8080/phpmyadmin__ . Click the Import tab, choose the file for _chommp.sql.zip_ in the project folder, and press go.
6. On a mac: Create a local server in the /web directory within the project folder  the command: __php -S localhost:8000__ .  On a windows, shrug.  Sorry, hoss.
7. Open the directory http://localhost:8000 in any standard web browser. (#chrome4lyfe)

## IF YOU NEED TO CREATE THE DATABASE

1. If you haven't already: In the terminal, start SQL by running the command: __mysql.server start__, and then run the command __mysql -uroot -proot__.
2. Run the command __CREATE DATABASE chomp;__ .
3. Use the database by running the command __USE chomp__ .
4. Create the __cuisine__ table by running the command __CREATE TABLE cuisine (name TEXT, id serial PRIMARY KEY);__ .
5. Create the __restaurant__ table by running the command __CREATE TABLE restaurant (rest_name TEXT, id serial PRIMARY KEY, location TEXT, price_range TEXT, cuisine_id INT);__ .
6. In your browser, navigate to http://localhost:8080/phpmyadmin.  The username is __root__ and the password is __root__.
7. Click on the _chomp_ database.
8. Click on the _Operations_ tab
9. Under _Copy database to_, name the copy __chomp_test__, select _Structure only_, unselect _Add contraints_ and _Adjust privileges_, then click _Go_.

## Known Bugs

Shrug!  Old project, remember?

## Support and contact details

If you have any questions, concerns, or feedback, please contact me through [gitHub](https://github.com/MBAllely/).
Or send me weird photos, like cats wearing socks.  I like those.

## Technologies Used

This web application was created using:
HTML, CSS, [Bootstrap](http://getbootstrap.com/), [Silex](http://silex.sensiolabs.org/),
[Twig](http://twig.sensiolabs.org/), [mySQL](https://www.mysql.com/),
and tested with [PHPUnit](https://phpunit.de/).

### License

This software is licensed under the MIT License.

Copyright (c) 2016 **_Marika Allely_** (our lord and savior)
