SBA 319 MongoDB Database Application

Overview

This is a RESTful API application built using Node.js, Express.js, and MongoDB. The application provides a platform for managing products and orders.

Features
Product Management: Create, read, update, and delete products.
Order Management: Create, read, and delete orders.
Validation: Validation rules for products.
API Endpoints

Products
Method	Endpoint	Description
GET	/api/products	Retrieves all products.
POST	/api/products	Creates a new product.
PUT	/api/products/:id	Updates an existing product.
DELETE	/api/products/:id	Deletes a product.
Orders
Method	Endpoint	Description
GET	/api/orders	Retrieves all orders.
POST	/api/orders	Creates a new order.
DELETE	/api/orders/:id	Deletes an order.


Troubleshooting

Error: Product not found: Check if the product ID is correct and the product exists in the database.
