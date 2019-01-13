# Bamazon
A Node app combine with my sequel


Description
This application implements a simple command line based storefront using the npm inquirer package and the MySQL database backend together with the npm mysql package. The application presents two interfaces: customer and manager.

To create the application first i went to github, and i created a new repository . I Copied the links and clone it to my computer. 

#To have this application Running
 You must install mysql Workbench to create the database 

 i created a file named it bamazon.sql this file is where i put my query to CREATE a new database and INSERT valueS into it . After that i log in to mySQL and copy paste evrythings and no errow was throw.

 i created two file one for bamazonCustomer.js and for bamazonManager.js

 #To Run The Commands
 To run the commands for the customer you will have to type 
 node bamazonCustomer.js 
 This Command will then show you a list of products that were inserted in the value of the database and by prompting a 
 question of the item would you like to purchase .You can only select the items by ID. 2nd Questions  is total of that Items you need , and it will tell you congratulations that the items you asked for is in stock and by giving you the total of your order and a Thank you message and it will send you back to the bamazon in case you like to buy a new items

 And for the bamazonMager.js 
 this command will show you 3 options 
 View products for sale 
 view low inventory
 add to inventory   
 Add New product

 if you selected for sale it will show all the list items that were added in the database and 
 if you selected Add new Product it will ask you the product Name department , the price per products 
 How many in Stocks and  message items is added and if you go on terminal you will see that product is added


  
