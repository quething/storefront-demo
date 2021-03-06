# Bamazon Storefront

## What Is This Thing?
An auction house app, using node.js and a local mySQL server to let users view and purchase items.

## How Do I Use It?
You'll need to install several packages first - inquirer and mySQL are both required for the app to function. You'll also need to provide your own local server password, either by editing the value of PASSWORD in the bamazoncustomer.js file directly, or by installing the dotenv package and assigning an appropriate key to a .env file. And of course, you'll need a mySQL database for the app to access - be sure that the database is named 'bamazon', and that the table 'products' has columns named item_id, product_name, price, and stock_quantity.

Once all the requirements are present, simply running the file in node should automatically lead you through the process, displaying any local store data and allowing the user to buy whatever they'd like.

![running the app](/assets/screen_9.png)

## Who Made It?
Scripting by Mars Getsoian, concept and package research by Trinity Coding Bootcamp.
