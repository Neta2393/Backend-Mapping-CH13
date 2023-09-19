# Backend-Mapping-CH13

![License Badge](https://img.shields.io/badge/license-MIT-green)


The following repo is the back end mapping for an e-commerce website that uses mysql, express, and sequelize. 

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

