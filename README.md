# -CRUD-APP
[CRUD] POST/GET/PUT/DELETE
CRUD-APP


-CRUD-APP README Introduction Welcome to -CRUD-APP, a simple and powerful CRUD (Create, Read, Update, Delete) application that allows you to perform basic operations on data entities. Whether you are building a web application, mobile app, or any other software that requires data management, -CRUD-APP has got you covered.

# Getting Started
To begin using -CRUD-APP, follow these steps: Make sure you install Node.js [ https://nodejs.org/en ] on your locall machine.

Install Dependencies: Navigate to the project directory and install the required dependencies.

run: npm install

[optional]: install nodemon package [ npm install -g nodemon ], it allows the server to start automatically without having to run [ node server.js ] but just [ node mom ] initially once.

Start the -CRUD-APP server by running the following command:
Run the Application: by typing: [ nodemon server.js ] or [ nodemon ] if installed. else run [ node server.js ].

By default, the application will run on [ http://localhost:7700/ ]. You can access the application through your web browser.

API Endpoints CRUD-APP provides the following API endpoints for managing data:

# POST: CREATE
[ /api/products/create ]
Create a new resource. Request Body: JSON with resource data.
[
{
productName: string,
prevPrice: int,
currPrice: int`,
category: string,
quantity: string
}
]


# GET: READ
[ /api/products/all ]
Retrieve details of all resource.

# GET: READ
[ /api/products/:id ]
Retrieve details of a specific resource. Parameters: id - Resource identifier.

# PUT: UPDATE
[ /api/products/:id ]
Update an existing resource. Parameters: id - Resource identifier. Request Body: JSON with updated resource data.

# DELETE: DELETE
[ /api/products/:id ]
Delete a resource. Parameters: id - Resource identifier.

# Conclusion
With CRUD-APP, you have a robust foundation for managing your data through simple API endpoints. Feel free to customize and extend the application based on your specific requirements.

Happy coding!
