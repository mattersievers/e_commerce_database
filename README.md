   # E-Commerce Database

  ## Table of Contents
  * [Description](#description)
  * [Install](#install)
  * [Use](#use)
  * [License](#license)
  * [Contributing](#contributing)
  * [Tests](#tests)
  * [Questions](#questions)

  ## Description
  This application acts as a back-end to an e-commerce website. It uses Sequelize to connect to a SQL database to store and sort Category, Product, and Tag model information. The application establishes api routes to perform the CRUD operations also known as the GET, POST, PUT, and DELETE routes.

  ## Install
  Be sure to have a a working SQL shell installed. To install the appropriate node modules use the command:  
   `npm install express sequelize mysql2 dotenv`  
  Ensure there is an environment ".env" file created in the root directory with the variables:
  
  `DB_NAME = 'ecommerce_db'`  
  `DB_USER = 'your_username'`  
  `DB_PW = 'your_password'` 
  
  along with the your_username and your_password information filled in with the appropriate information to access the SQL database. Use the command:  
   `mysql -u your_username -p`  
  with your_username filled in and type your password when prompted. Use the command:    
   `source db/schema.sql`  
  to create the SQL database and quit out of the shell. Use the command:  
   `npm run seed`  
  if you would like to populate to database with dummy information to observe the application in progress. 
    
  ## Use
  Use the command:  
   `node server`  
  to initiate the server. The GET routes can be checked through either a browser or through an interface like Insomnia Core. The POST, PUT, and DELETE routes may also be tested through Insomnia Core.
  
  ## License
  No license.

  ## Contributing
  [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)

  ## Tests
  No tests were constructed for this application.
  
  ## Questions
  - [Github for mattersievers](http://www.github.com/mattersievers)
  - For further questions, contact me through email at mattersievers@gmail.com

