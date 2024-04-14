# **E-Commerce API**

This will show you how the E-Commerce API works and how to get started using it.

## ·Features· 

**✅ Customer Management:** *Create, retrieve, update, and delete customers.*

**✅ Product Management:** *Add, view, update, and remove products.*

**✅ Order Management:** *Create, view, update, and delete orders.*

**✅ Database Interaction:** *Utilizes SQLAlchemy to interact with the database efficiently.*

**✅ Validation:** *Implements data validation using Marshmallow to ensure data integrity.*

**✅ Error Handling:** *Provides detailed error messages and proper HTTP status codes for better debugging and user experience.*
<br />

## ·Usage·
***The API provides endpoints for managing customers, products, and orders.***

<br />

**Customers:**

**✅("/customers", methods = ["GET"])**: Get all customers.

**✅("/customers/<int:id>", methods = ["GET"])**: Get a customer by ID.

**✅("/customers", methods = ["POST"])**: Create a new customer.

**✅("/customers/<int:id>", methods = ["PUT"])**: Update a customer.

**✅("/customers/<int:id>", methods = ["DELETE"])**: Delete a customer.

**Products:** 

**✅("/products", methods = ["GET"])**: Get all products.

**✅("/products/<int:id>", methods = ["GET"])**: Gets a products by ID.

**✅('/products', methods = ["POST"])**: Create a new product.

**✅("/products/<int:id>", methods = ["PUT"])**: Update a product.

**✅("/products/<int:id>", methods = ["DELETE"])**: Delete a product.

**Orders:** 

**✅("/orders", methods = ["GET"])**: Get all orders.

**✅("/orders/<int:id>", methods = ["GET"])**: Get orders by ID.

**✅("/orders", methods = ["POST"])**: Create a new order.

**✅("/orders/<int:id>", methods = ["PUT"])**: Update an order.

**✅("/orders/<int:id>", methods = ["DELETE"])**: Delete an order.

<br />

*Refer to the API documentation for detailed usage instructions.*


## ·Error Handling·
 *The API provides detailed error messages and appropriate HTTP status codes to handle various scenarios such as invalid requests, missing data, or database errors. Error responses are formatted in JSON for easy interpretation by client applications.*

 ## Authors

**This application was a group effort created by:**     

*Chris Fletcher* https://github.com/cfletcher84

*Savannah Lyles* https://github.com/Savvy325
