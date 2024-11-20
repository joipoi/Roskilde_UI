# Description
This is a project I made for my dad and his friends. It is used to manage a music competition where users vote on their favorite songs of the year. This is something that is held once a year between some friends.

The frontend is javascript and the backend is Java Spring Boot. I also use maven. 

# Usage
To connect to the database you need to setup Enviroment Variables. These are the ones you will need:
- DB_USERNAME (the username for your mysql user)
- DB_PASSWORD (the password for your mysql user)
- DB_url (the url for your database, example: jdbc:mysql://hostname:port/database)

You can import the database I used with the help of the dump.sql file. It should create the database and the tables required to run the program. It will however not import any data so the tables are empty.

# Files

## Backend
- Main.java
- Mapping.java
- Song.java

## Frontend
- admin.html
- login.html
- results.html
- user.html
- userEditing.html
- votes.html
- script.js
- stylesheet.css
