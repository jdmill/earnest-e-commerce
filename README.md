# earnest-e-commerce
https://github.com/jdmill/earnest-e-commerce/

## Task
Build the back end for an e-commerce site by configuring a working Express.js API to use Sequelize to interact with a MySQL database

## User Story

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
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```

## Installation
1. npm i
2. source schema.sql -create the db using mySQL2
3. USE ecommerce_db
4. node seeds/index.js -seeds db

## Demonstration


https://user-images.githubusercontent.com/9371206/165850134-6b7d2c4d-6610-4508-a548-539abfa111a9.mp4

