# E-Commerce Back End

## Link to my repo: https://github.com/wasmulb/e-commerce-back-end

## Link to tutorial video: https://drive.google.com/file/d/1jsysOc7b5r6VuO3itprC_EFLTzCwH0nk/view

## Description

For this assignment, I developed a back-end database for an e-commerce website. This database has three models: categories, tags, and products. The user is able to perform server requests to search in the models, search by ID in the models, create, update, and delete. 

The server runs by using express, and uses sequelize to interact with the database. This was my first time using sequelize. I found it to be very useful, and it allows more flexibility in syntax than raw sql. The biggest challenge of the assignment was making my associations. I had to read a lot of documentation and performed lots of debugging to get my associations worded correctly. 

## Installation

After cloning the repo to your local environment, install dependencies by "npm install" in the terminal. Next, run the schema.sql file to create the database. Next, seed your database by running the index.js in the seeds directory.

## Usage

After completing the steps in the Installation section, enter your sql credenials in the config file, or add them to .env file. Run the server.js file. Once the server is online, use Insomnia or similar software to perform the server requests. Check out my tutorial video to see all server requests.

## License

The MIT Licence was used for this assignment.
