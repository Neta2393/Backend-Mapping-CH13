# Backend-Mapping-CH13

![License Badge](https://img.shields.io/badge/license-MIT-green)


The following repo is the back end mapping for an e-commerce website that uses mysql, express, and sequelize. You can find the code for this challenge at https://github.com/Neta2393/Backend-Mapping-CH13

## Table of Contents:

**1.[User-Story](#user-story)**

**2.[Acceptance-Criteria](#acceptance-criteria)**

**3.[Installation](#installation)**

**4.[Walkthrough](#walkthrough)**

**5.[Challenges](#challenges)**

**6.[Sources](#sources)**

**7.[Contribute](#contribute)**

**8.[GitHub](#github)**


## User-Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
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

## Installation

Cloned the starter code for Challenge 13

Ran npm i sequelize, mysql, and dotenv

Login to mysql from the command line using mysql -u root -p

Created the ecommerce_db

Seeded the data and opened insomnia to view the RESTFUL API


## Walkthrough
[ORM-ECommerce.webm](https://github.com/Neta2393/Backend-Mapping-CH13/assets/128006949/d43045d0-8397-4ed9-9eb4-da6179aff6ea)

## Challenges

The biggest challenge was revisiting Insomnia and having to restart due to accidentally cloning the Develop folder. 

## Sources

Challenge 13 Starter Code

https://docs.insomnia.rest/insomnia/environment-variables   (Read up on docs on Insomnia to help because I am rusty on Insomnia)

https://www.techonthenet.com/sql_server/foreign_keys/drop.php  (When recreating the code I ran into a foreign Key error this webpage helped me to fix that error)


## Contribute

To contribute please clone and reach out at https://github.com/Neta2393/Backend-Mapping-CH13

## Github

Benethea Hardin https://github.com/Neta2393




