# WILDLIFE TRACKER
Wildlife tracker is a database-supported Java website designed to help wildlife rangers keep track of wild animals in the event of a clearing. Rangers can add endangered and non-endangered animals to the website, and then record each sighting of the animals. Also, they can view a table of all sightings and all animals added to the database.


<img src="https://i.ibb.co/DtfCfgV/Screenshot-from-2019-05-02-10-06-13.png">
<img src="https://i.ibb.co/cT4hjQj/Screenshot-from-2019-05-02-10-12-34.png">
<img src="https://i.ibb.co/Cb6XhYW/Screenshot-from-2019-05-02-10-07-01.png">
<img src="https://i.ibb.co/MPBtYQV/Screenshot-from-2019-05-02-10-07-39.png">
<img src="https://i.ibb.co/RhPHKJP/Screenshot-from-2019-05-02-10-07-48.png">


## Project Setup
* Clone this project at [Wildlife Tracker](https://github.com/koros99/Wildlife-tracker)
* On the terminal, navigate to the downloaded project directory and run the following commands:
```
$ psql

user=# CREATE DATABASE wildlife_tracker;

user=# \q

$ psql wildlife_tracker < wildlife_tracker.sql 

$ psql

user=# CREATE DATABASE wildlife_tracker_test WITH TEMPLATE wildlife_tracker;

user=# \q

```

* Go to the project directory on the terminal and run `gradle run` 
* Open your website on `localhost:4567` to view the website.

## BDD
* Users are able to add endangered and non-endangered animals to the website.
* Users are able to report a sighting of each animal.
* Users are able to view a list of all endangered and non_endangered animals.
* Users are able to view all reported sightings.
* Users are able to view all sightings of a specific animal.

## Dependencies
1. Java
2. Gradle
3. Postgres

## Technologies Used
1. Java
2. HTML
3. CSS
4. Postgress(psql)

## Author and Contact Information
Written by [Victor Kilel](https://github.com/koros99). Email: vickiekross99@gmail.com.

## Licence
Licenced under [The MIT Licence](https://github.com/koros99/Wildlife-tracker/blob/master/LICENCE) Copyright(c) 2019 Victor Kilel.