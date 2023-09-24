<h1 align="center">Object-Relational Mapping (ORM): E-Commerce Back End</h1>

<div align="center">
   Solution for a challenge from  <a href="https://git.bootcampcontent.com/University-of-California---Irvine/UCI-VIRT-FSF-PT-06-2023-U-LOLC/-/tree/main/13-ORM/02-Challenge" target="_blank">University of California - Irvine
UCI-VIRT-FSF-PT-06-2023-U-LOLC</a>.
</div>

<div align="center">
  <h3>
    <a href="https://github.com/drbv27/OrmChallenge">
      Solution
    </a>
    <span> | </span>
    <a href="https://git.bootcampcontent.com/University-of-California---Irvine/UCI-VIRT-FSF-PT-06-2023-U-LOLC/-/tree/main/13-ORM/02-Challenge">
      Challenge
    </a>
  </h3>
</div>

<p align="center">
    <img src="https://img.shields.io/github/repo-size/drbv27/OrmChallenge" />
    <img src="https://img.shields.io/github/languages/top/drbv27/OrmChallenge"  />
    <img src="https://img.shields.io/github/issues/drbv27/OrmChallenge" />
    <img src="https://img.shields.io/github/last-commit/drbv27/OrmChallenge" >
    <a href="https://github.com/jpd61"><img src="https://img.shields.io/github/followers/drbv27?style=social" target="_blank" /></a>
</p>

<p align="center">
    <img src="https://img.shields.io/badge/Javascript-yellow" />
    <img src="https://img.shields.io/badge/express-orange" />
    <img src="https://img.shields.io/badge/Sequelize-blue"  />
    <img src="https://img.shields.io/badge/mySQL-blue"  />
    <img src="https://img.shields.io/badge/dotenv-green" />
</p>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Mock-up](#mock-up)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Description](#description)
- [Installation](#installation)

<!------------Mock-up------------>
## Mock-up

The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia:

![screenshot](https://github.com/drbv27/OrmChallenge/blob/main/animations/13-orm-homework-demo-01.gif)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia:
![screenshot](https://github.com/drbv27/OrmChallenge/blob/main/animations/13-orm-homework-demo-02.gif)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia:
![screenshot](https://github.com/drbv27/OrmChallenge/blob/main/animations/13-orm-homework-demo-03.gif)

<!------------User Story------------>
## User Story
  
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

<!------------Acceptance Criteria------------>  
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

<!------------Description------------>
## Description

A scalable e-commerce backend built with MySQL, Express, Sequelize, and dotenv.
  
I've included a gif below to show you how the application works.

![GET Operations](https://github.com/drbv27/OrmChallenge/blob/main/animations/GetOps.gif)


![POST PUT DELETE Products and Tags](https://github.com/drbv27/OrmChallenge/blob/main/animations/PostDelete.gif)

<!------------Installation------------>
## Installation
  
`npm init`

`npm install mysql2`

`npm install sequelize`

`npm install dotenv`


<!------------Usage------------>
## Usage
  
you need to have previously installed mysql server on your PC.
<a href="https://www.mysql.com/downloads/">MYSQL</a>
Run the following command at the root of your project and answer the prompted questions:

`mysql -u root -p`

Enter PW when promted

`source db/schema.sql`

`quit`

`npm run seed`
  
`npm start`

Now you can use: 
<a href="https://insomnia.rest/download">Insomnia</a>
or
<a href="https://www.postman.com/">Postman</a>

For use the CRUD operations

## Contributing
:octocat: [Diego Bonilla](https://github.com/drbv27)

## Questions
Contact me with any questions: [email](mailto:drbv27@gmail.com) , [GitHub](https://github.com/drbv27)<br />