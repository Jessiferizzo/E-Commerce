<h1 align="center"> E-Commerce Back End</h1>  
  
<h3 align="center">::(ORM Challenge):: </h3>

  # Description
  A mysql database and application backend for an e-commerce site that encompasses using MySQL2, Express, Sequelize and dotenv.

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
  
  # Table of Contents
  * [Site](#site)
  * [Installation](#installation)
  * [Usage](#usage)
  * [Questions](#questions)
  * [License](#license)
  
  # Site 
  [E-Commerce Github Repo](https://github.com/Jessiferizzo/E-Commerce.git)


  ## Built With:
  Node, Express, Mysql2, Sequelize,  Dotenv
  
  # Installation
  💾 
  `npm install`
  
  # Usage
  1. First user must clone the repo, create a `.env` file with associated passwords. 

  2. Sign into `mysql` account by running `mysql -u root -p` at the terminal, enter your password when prompted, then run `source db/schema.sql`, quit `mysql` with `\q`.
  
  3. At terminal, run `node seeds/index.js` to populate seeds data, then `npm start` to start up server. 

   📷 
   ![gif of app](./public/images/habitual%20_%20Habit%20Tracker.gif)
  

  ## Contributing
   no contributions at this time
  
  ## Questions
  Please contact me using the following links:

  :octocat: Github [Jessiferizzo](https://github.com/jessiferizzo) 

  ## Acknowledgments
 MIT licensing, our great instructors and TAs, graders, and classmates

  ## License
  [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
  Read more about MIT here:
  [MIT](https://opensource.org/licenses/MIT)

  Copyright (c) 2022 