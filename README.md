# Surf & Shop


## Table of Contents
* [Description](#description)
* [The Challenge](#challenge)
* [The Criteria](#criteria)
* [Installation](#install)
* [Usage](#usage)

## Description <a name="description"></a>
Database for an ecommerce website where you can GET, POST, PUT, and DELETE categories, products, and product ags.

![Surf & Shop](./screenshot/surf-and-shop.gif)
[Click here to watch video]()

## The Challenge <a name="challenge"></a>
AS A manager at an internet retail company I WANT a back end for my e-commerce website that uses the latest technologies SO THAT my company can compete with other e-commerce companies

## The Criteria <a name="criteria"></a>
GIVEN a functional Express.js API
1. WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
    * THEN I am able to connect to a database using Sequelize
1. WHEN I enter schema and seed commands
    * THEN a development database is created and is seeded with test data
1. WHEN I enter the command to invoke the application
    * THEN my server is started and the Sequelize models are synced to the MySQL database
1. WHEN I open API GET routes in Insomnia Core for categories, products, or tags
    * THEN the data for each of these routes is displayed in a formatted JSON
1. WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
    * THEN I am able to successfully create, update, and delete data in my database

## Installation <a name="install"></a>
After cloning the code, use npm install to install dependecies. Create an .env file and paste the following code:

DB_NAME='ecommerce_db'
DB_USER=''
DB_PW=''

Add your MySQL username and password and save. Open your MySQL command line and type "npm run start" to initalize the database and then type exit. After the database has been created and you exited, type "npm run seed" into the MySQL command line to populate the database.

Run "npm run start" again to restart the server. Open Insomnia Core and begin testing routes.

## Usage <a name="usage"></a>
MIT License

Copyright (c) 2021 Ian Jackson

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE. 