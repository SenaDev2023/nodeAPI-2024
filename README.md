# nodeAPI-2024
Simple CRUD app with Javascript, Express and MongoDB


Javascript: Serves as the backbone programming language for the application, used both on the client-side and server-side (Node.js).

Express: A minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications. It's used to create the server and define API endpoints for handling HTTP requests.

MongoDB: A NoSQL, document-oriented database designed for ease of development and scaling. It stores data in flexible, JSON-like documents.

CRUD Operations:

Create: Adding new data to the database, typically through a POST request to an Express route that handles the insertion of data into MongoDB.
Read: Retrieving and displaying data from the database, typically through GET requests. Express routes handle these requests and fetch data from MongoDB.
Update: Modifying existing data in the database, usually through PUT or PATCH requests. Express routes will handle the logic to update records in MongoDB.
Delete: Removing data from the database, typically via DELETE requests. Express routes are set up to handle the deletion of records in MongoDB.
The app would typically also involve some form of user interface, created using HTML/CSS and enhanced with JavaScript, to make the CRUD operations user-friendly and accessible through a web browser.

For an effective CRUD application, you would also want to implement form validation, error handling, and potentially user authentication to manage access to the data
