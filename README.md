# E-Commerce-Backend



A back-end e-commerce platform that uses RESTful API calls combined with an SQL powered database to store data in order to create, read, update and delete items.

## Table of Contents

* [Technologies](#technologies)
* [Installation](#installation)
* [Usage](#usage)
* [Live Demo](#live-demo)
* [Resources](#resources)
* [Contact](#contact)

## Technologies
This application was built using the following technologies and languages:
* [Node.js](https://nodejs.org/en/)
* [Express.js](https://expressjs.com/)
* [MySQL 2 NPM](https://www.npmjs.com/package/mysql2)
* [Sequelize](https://sequelize.org/)
* [dotenv NPM](https://www.npmjs.com/package/dotenv)
* [Nodemon](https://www.npmjs.com/package/nodemon)
* [Insomnia](https://insomnia.rest/)
* JavaScript
* SQL (via Sequelize)

## Installation

To run the E-commerce Back End, you'll first need to clone the repo or download the zipfile then install node.js, and other dependencies. To test the API requests, you'll need to install Insomnia, or a similar API client, such as Postman.

To install the dependencies included in this repo, navigate to the root directory of the cloned or downloaded repo. In either your terminal, command line or using the integrated terminal in your code editor of choice, enter the following command:

`npm i`

OR

`npm install`

If you're including the `package-lock.json` file from this repo in your own files, then run the following command instead:

`npm ci`

## Usage

To use the Ecommerce Back End, clone or download the repo and install the dependencies as instructed above.

Next, you'll need to source the database in your SQL database by navigating to the db folder. Then access your SQL database and enter:

`SOURCE schema.sql`

You can then add seed data if you wish. To do so, navigate to the root folder in either your terminal, command line or using the integrated terminal in your code editor of choice and enter:

`npm run seed`

Next, to begin the application enter:

`npm start`

You can then make API requests and update data in Insomnia or your API client of choice.

Responses will be printed in the API client.

## Live Demo

 API requests are tested in Insomnia. 
### [Please click here for live demo](https://drive.google.com/file/d/1i-jk-h3mE2D29BuCblCQAQpcdPWrUz_b/view)

## Resources
* [Sequelize Documentation](https://sequelize.org/docs/v6/getting-started/)

## Contact
Amir Esfandiari 
 - email: amir.esf1983@gmail.com
- Github: https://github.com/amiresf1983/





