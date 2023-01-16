# InStock
Instock is an Agile project to deliver a full stack Inventory Management System with a modern React and SCSS front-end communicating with a robust Express, Nodejs back-end. Source of data is a MySQL database using knex.js to interact with the db. The website is fully responsive for mobile, tablet, and desktop viewing and users can add, edit or delete both warehouses and inventory items (full CRUD operations). 

Instock is a collaborative project made by myself and three other developers. We all got to work with both front-end and back-end technologies. I was responsible for the building process and functional aspects for the following React components: Header, Add New Inventory Item and Edit Inventory Item. We all had the chance to act as the project manager using Jira Software to assign the daily tasks and making sure we were on top of the deadlines. Figma was used for the interface design.

## The Team

This project was built with the collaboration of: <br>
[Nanaya Miki](https://github.com/Lala0419) <br>
[Hester L](https://github.com/hlai52) <br>
[Emily Wong](https://github.com/emwong101) <br>


## Tech Stack and Tools
* HTML, SASS, JavaScript, React, React Router, Node, Express, API's , MySQL, Knex.js, Postman, Axios, Jira and Figma.

## Installation:
1. To install and run the project you will need to clone or dowload the Front-end file - [instock](https://github.com/NacarateJ/instock), and the Back-end file - [instock-api](https://github.com/NacarateJ/instock-api);
2. Run ```nmp i``` to install all the required packages for the app;
3. To start the Front-end run the command ```npm start```;
4. To start the Back-end run the command ```npm run server```;

## Environment Variables
1. Front-end:
Add the following variables in .env file:

```REACT_APP_API_URL=https://localhost:8080```
  
2. Back-end:

```DB_LOCAL_DBNAME="instock_api"```<br>
```DB_LOCAL_USER="YOUR DB USER NAME"```<br>
```DB_LOCAL_PASSWORD="YOUR DB PASSWORD"```<br>
```PORT = 8080```

## To connect to DB and data seeding

To connect the server with the databse we used a SQL query builder, knex.js. 

Install knex.js if it has not yet been installed:

```npm install knex --save```

Create a new database named "instock_api" on your local machine using the [mysql client tool](https://www.mysqltutorial.org/mysql-create-database/).

Once the database has been created, run the latest migration file to build the database table. To do this run the command as follows:

```npm run migrate```

Once the tables have been created we can seed them to populate the tables with data. To do this run:

```npm run seed```


## Demo

<div align="center">

https://user-images.githubusercontent.com/114256348/212584656-00db1837-90e9-461d-8b16-d0b3de33f61c.mp4

  </div>
