# E-Commerce Backend • [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description
Mock e-commerce backend application that interacts with a MySQL database upon calling a specific route. Sequelize.js employed as ORM for initial database setup. APIs tested using Postman.
## Video Demonstration of Application
* [Click Here](https://github.com/eddyK15501/ecommerce-backend/issues/1#issue-1874063451)
## Installation
* Required: LTS or latest version of Node.js
* Required: LTS or latest version of MySQL
* Required: Postman or Insomnia
## Usage
* #### Clone the repository:

<img width="450px" src="https://user-images.githubusercontent.com/88423414/264437246-a2593dbf-6547-4237-84d7-8ada453e311f.png" />

* #### Inside the repo, make a .env file and define the following process.env variables:
```
DB_NAME='ecommerce_db'
DB_USER='root' 
DB_PASSWORD='your_mysql_password' 
```

* #### Open a terminal window and navigate to the repository directory. Connect to MySQL server and create a new database:
```
mysql -u root (-p for password)
SOURCE ./db/schema.sql;
```

<img width="750px" src="https://user-images.githubusercontent.com/88423414/264452469-c2d46956-db7e-4457-b4d6-3084abbb0d4e.png" />

* #### Exit MySQL command-line. Then, enter the following commands:
```
npm install
npm run seed
npm run watch
```

* #### The localhost server will be active on port 3001. Test the APIs by accessing the routes within the ./routes/api directory using the appropriate HTTP methods. Postman being utilized in this example:

<img width="900px" src="https://user-images.githubusercontent.com/88423414/264454785-18b85344-e986-475b-8bc4-fe66846f0a78.png" />

## Credits
* To my persistent classmates at the UNC coding bootcamp.
* Written by Edward Kim.

## License
This application is covered under the [MIT License](./LICENSE).