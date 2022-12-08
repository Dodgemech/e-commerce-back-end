# E-Commerce Backend
## Description
A Sequelize backend database for an e-commerce application.
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
## Technologies
- JavaScript
- MySQL
- Node
- Express.js
- Dotenv
- Sequelize
- My SQL2
## Installation
1. Clone this repo to your local machine using ```Git Clone```.
2. Navigate to the root directory of this application.
3. Run ```npm i``` to install necessary dependencies.
4. In an integrated terminal within the root directory, run ```mysql -u root -p``` to access MySQL.
5. Run ```source db/schema.sql```.
6. Exit MySQL by using the command ```quit```.
7. Seed the database using the command ````npm run seed```.
8. Enter the command ```node index.js``` to start the application.
## Demo
