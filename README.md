Project Overview

This project focuses on building the back end of an e-commerce platform for an online retail company. It utilizes Express.js, PostgreSQL, and Sequelize to create, seed, and manage a database of product information. The application supports full CRUD functionality, allowing for the creation, reading, updating, and deletion of product data.
Installation Instructions

    Clone the Repository:
        Begin by cloning this repository to your local machine.

    Install Dependencies:
        Initialize Node.js by running the following command:

        bash

npm init -y

Install the necessary dependencies:

bash

    npm i

Configure Environment Variables:

    Create a .env file in the root directory. This file should contain the database name and your PostgreSQL login credentials.

Set Up PostgreSQL Database:

    Set up your PostgreSQL database by running the following command in your terminal:

    bash

psql -U postgres

Enter your PostgreSQL username and password when prompted.
Once inside the PostgreSQL CLI, create the database by executing the schema file:

bash

\i schema.sql

Seed the database with sample data:

bash

        npm run seed

Usage Instructions

    Run the Application:
        After completing the installation, open the cloned repository in a code editor like Visual Studio Code.
        Start the application by running the following command in an integrated terminal:

        bash

    npm start

Test API Endpoints:

    You can test the API routes using tools like Insomnia or Postman by following the provided API endpoints.