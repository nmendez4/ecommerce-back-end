# E-Commerce Back End
Object-Relational Mapping (ORM) Challenge 

## Installation
```
In order to install this application please visit https://github.com/nmendez4/ecommerce-back-end/ and download the code
```

## Usage
```
In order to use this application please have VS Code and Insomnia or some other coding application downloaded. From there please run npm install, and download node, express, sequelize. Then using MYSQL, create your database, use that database and then seed it with schema.sql. From there you will run npm start and the server should be listening on the localhost, in this case is 3001.
```

## Built With
* Node.js
* Express.js
* Sequelize
* ORM
* Insomnia

## Screenshots
![Screenshot-of-VS-Code-and-Insomnia](/assets/e_commerce-ORM.png)

## Author
Nicholas Mendez

## User Story
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria
```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```
