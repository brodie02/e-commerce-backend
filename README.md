# Coding Bootcamp Week 13 Challenge - E-Commerce Back End

## Description

This weeks challenge focused on creating a back end for an e-commerce website. This application can manipulate the database which stores the websites data, this includes the products the website may sell. The user can view, add, update and even delete different products, categories and tags.

## Built With

* JavaScript
* NodeJS
    * Sequelize Package
    * Express Package
    * MySQL2 Package
    * Dotenv Package    
* SQL


## Installation and Usage

Below are instructions on how to install and use this application:
```json
npm install
```
Create a .env file with the following content (your MySQL username and password)
```json
DB_NAME='ecommerce_db'
DB_USER=''
DB_PASSWORD=''
```
Login to your MySQL
```json
mysql -u root -p
```
To create the database
```json
source db/schema.sql
```
Exit MySQL
```json
quit
```
To populate the database
```json
node seeds/index.js
```
Finally you can start the application
```json
npm start
```

Once the application has been properly installed, you can use Insomnia to view and manipulate the data from the database.

Below is a walkthrough video to show how the applications runs.

https://youtu.be/Sii0dE8F2Bo

## Credits

Made by [Brodie Marshall](https://github.com/brodie02)

---