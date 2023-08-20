# e-commerce-backend

## Description
This project serves as the foundation of the technical workings behind an online shopping website. It's constructed using Express.js and Sequelize to interact with a MySQL database, enabling users to effectively oversee categories, products, and tags within the digital store.

The driving force motivating this endeavor is to establish a fully operational backend for the e-commerce website, employing the latest technologies and industry best practices in web development. This strategic approach positions the company to effectively compete in the expanding realm of online commerce.

This project effectively tackles the challenge of efficiently managing and structuring product data within the e-commerce platform. This is achieved by providing specific pathways through APIs to create, read, update, and delete categories, products, and tags. This streamlined approach facilitates effective management of the online store's inventory.

Through this project, I gained a comprehensive understanding of how to set up a backend API using Express.js and Sequelize, create and establish connections between different database models, ensure sensitive data security through environment variables, and implement smooth and comprehensive CRUD operations to efficiently manage data.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation
To install and run the application, follow these steps:
1. Clone the repository to your local machine.
2. Navigate to the project directory in the terminal.
3. Run the following command to install the required dependencies: npm install
4. Create a .env file in the root directory and add your MySQL database details as follows:
- DB_NAME=your_database_name
- DB_USER=your_mysql_username
- DB_PASSWORD=your_mysql_password
5. Set up your MySQL database by executing the SQL commands provided in the seeds.sql file. This will create the necessary tables and populate them with sample data.
6. Update the database connection configuration in the server.js file with your MySQL credentials.
7. Seed the database by running the following command line: node seeds/index.js
7. Start the application server by running the following command: npm start

## Usage
This project provides API routes to manage categories, products, and tags for an e-commerce website. You can test these routes using tools like Insomnia or Postman.

API Routes
* Categories:
    GET /api/categories: Get all categories.
    GET /api/categories/:id: Get a single category by ID.
    POST /api/categories: Create a new category.
    PUT /api/categories/:id: Update a category by ID.
    DELETE /api/categories/:id: Delete a category by ID.
* Products:
    GET /api/products: Get all products.
    GET /api/products/:id: Get a single product by ID.
    POST /api/products: Create a new product.
    PUT /api/products/:id: Update a product by ID.
    DELETE /api/products/:id: Delete a product by ID.
* Tags:
    GET /api/tags: Get all tags.
    GET /api/tags/:id: Get a single tag by ID.
    POST /api/tags: Create a new tag.
    PUT /api/tags/:id: Update a tag by ID.
    DELETE /api/tags/:id: Delete a tag by ID.

Git Hub Repository:
https://github.com/calzu0821/e-commerce-backend.git

Walkthrough Video: 
https://drive.google.com/file/d/1JkqntyVCfu9wJjTDt1fw07RubbxgLIZ3/view?usp=sharing

Watch the Walkthrough Video to see the functionality of the e-commerce back end in action. The video demonstrates the following:

- Creating the database schema from the MySQL shell.
- Seeding the database with test data.
- Starting the application server.
- Testing various API routes using Insomnia, including GET, POST, PUT, and DELETE operations for categories, products, and tags.

## Credits
I used the following third-party assets in this project:
- https://sequelize.org/master/
- https://sequelize.org/master/manual/model-basics.html
- https://sequelize.org/master/manual/model-basics.html#data-types
- https://sequelize.org/master/manual/assocs.html
- https://sequelize.org/master/manual/model-querying-basics.html
- https://sequelize.org/master/manual/model-basics.html#taking-advantage-of-models-being-classes
- https://sequelize.org/master/manual/validations-and-constraints.html
- https://www.npmjs.com/package/dotenv
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/try...catch
- https://developer.mozilla.org/en-US/docs/Web/HTTP/Status

## License
N/A