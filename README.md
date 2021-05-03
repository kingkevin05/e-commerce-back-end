# e-commerce-back-end

## Description 
  This is the back-end for an e-commerce site that works with Express.js API and configures it to use Sequelize to interact with a MySQL database.
 
  
  ## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  
  
  ## Installation
  
 `npm install` in order to install the following npm package dependencies as specified in the package.json:

* [`inquirer`](https://www.npmjs.com/package/inquirer) that will prompt you for your inputs from the command line

* [`mysql2`](https://www.npmjs.com/package/mysql2) to connect to your MySQL database and perform queries

* [`express`](https://www.npmjs.com/package/express) is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.

* [`sequelize`](https://www.npmjs.com/package/sequelize) is a promise-based Node.js ORM tool for Postgres, MySQL, MariaDB, SQLite and Microsoft SQL Server.

* [`dotenv`](https://www.npmjs.com/package/dotenv) is a zero-dependency module that loads environment variables from a .env file into process.env

* [`nodemon`](https://www.npmjs.com/package/nodemon) a tool that helps develop node.js based applications by automatically restarting the node application when file changes in the directory are detected.

 - To create the `ecommerce_db` database:
    - type `mysql -u root -p` at the command line to start your sql server and enter your password when prompted
    - at the mysql prompt, type `source db/schema.sql` to migrate the tables structure and relations
    - at the mysql prompt, type `quit`

  - In the command line run `npm run seed`
  
  - In the `.env` file, enter your database name, MySQL username, and MySQL password

Run the app with `npm start` in the command line.
  
  ## Usage
  
  ![Gif demo of get all](https://github.com/kingkevin05/e-commerce-back-end/blob/main/images/getAll.gif)

  ![Gif demo of get one](https://github.com/kingkevin05/e-commerce-back-end/blob/main/images/getOne.gif)

  ![Gif demo of post put delete](https://github.com/kingkevin05/e-commerce-back-end/blob/main/images/Post.gif)

![screenshot2](https://github.com/kingkevin05/e-commerce-back-end/blob/main/images/Screenshot1.png)


  ---
  
  ## Questions?
  
  ![Developer Profile Picture](https://avatars.githubusercontent.com/u/75460766?v=4) 
  
  If you have any question please feel free to reach out:
 
  GitHub: [@kingkevin05](https://api.github.com/users/kingkevin05)