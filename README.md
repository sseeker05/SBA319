SBA 319 MongoDB Database Application

Description

This is a RESTful API application built using Node.js, Express.js, and MongoDB. The application provides a platform for managing products, users, and orders.
API Endpoints

Products
GET /api/products: Retrieves a list of all products.
POST /api/products: Creates a new product.
PUT /api/products/:id: Updates an existing product.
DELETE /api/products/:id: Deletes a product.
Users
GET /api/users: Retrieves a list of all users.
POST /api/users: Creates a new user.
PUT /api/users/:id: Updates an existing user.
DELETE /api/users/:id: Deletes a user.
Orders
GET /api/orders: Retrieves a list of all orders.
POST /api/orders: Creates a new order.
DELETE /api/orders/:id: Deletes an order.

Example Usage
Create a new product: Send a POST request to /api/products with the product details in the request body.
Retrieve all products: Send a GET request to /api/products.

Troubleshooting

Error: Product not found: Check if the product ID is correct and the product exists in the database.
Error: User not found: Check if the user ID is correct and the user exists in the database.
