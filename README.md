# eShopping-platform
CSC 131 repository for our eShopping Platform project

## Project information:
Our project is a shopping website that allows users to manage a shopping cart and place orders. Shoppers are also allowed to login, search and browse products, favorite products, remove or add to the shopping cart, have them provide their address and make payments using a card. Admin access and inventory management will also be supported. For this second iteration of our eShopping Prototype, we are developing the database tier for our platform using SQlite. 

## Database:
The data that the project will store on a secondary storage includes user and admin information, payment information, shopper addresses, products and their details, product quantities, shopping carts, orders and favorite products. This data will be used to manage purchases, process deliveries and payments, take care of inventory management, manage customer and admin accounts and keep track of shopping cart activity

## Represented in NoSQL:
If we chose to use No_SQL, we could use a database such as MongoDB to store our data in a document database. For example, one object we could create would be the shopping cart. Each product in the shopping cart would also be an object. This would allow us to create one document for a cart, which can contain multiple products. The keys could be int item_id, string item_name, int quantity and double cost. An example of values for these keys for the item would be 123, “Apple”, 5, and 3.75. 

## Summary:
For our database project, we chose SQLite, as it is a serverless DBMS that has the ability to run within applications. We decided on this because we wanted to start with a smaller database that would specifically display our category, cart, item, and cart_item tables. We wanted to make this iteration more of a demonstration of what our database will hold by presenting these 4 tables. With this iteration it was a bit difficult to work with our team since we were not able to meet in person and we communicating through Discord, however we were all able to bring up thoughtful pieces to the project and collaborate effectively to ensure that we had the same idea of what we wanted to do for this iteration.

## INdividual Reflection:
Hailey: 

Fatema:  

Kylie:
    
Joe:
