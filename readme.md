<p align="center">
  <a href="https://expressjs.com/" target="blank"><img src="https://miro.medium.com/v2/resize:fit:1400/1*XP-mZOrIqX7OsFInN2ngRQ.png" width="200" alt="Express Logo" /></a>
</p>0

## Description

This project is a web application that allows you to create authors, books, and upload book images. The application is built using Node.js and Express, and it utilizes a MySQL database to store the information of authors and books.

## CRUD

1. Create, read, update and delete authors.
2. Create, read, update and delete books.

## Technologies

1. Express
2. Mysql
3. Sequelize
4. Express-validator

## Requirements

Before running the project, make sure you have Node.js installed. You can use Docker with MySQL, Docker, or Nodemon on your machine.

## Installation of the project

1. Clone the repository.
2. Install the dependencies with the command `npm install`.
3. Create a file called `.env` in the root of the project and copy the content of the file `.env.template` in the `.env` file.
4. Add the environment variables in the `.env` file.
5. If you are usin Docker, you must run the command: `docker-compose up -d` to start the database.
6. If you are not usin Docker, you must create the database manually.
7. Run the command: `npm run dev` to start the project in development mode.
