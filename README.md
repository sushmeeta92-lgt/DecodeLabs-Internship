Backend API Development – Week 2 Internship Project

Overview

This project demonstrates the development of a simple RESTful Backend API. The API handles user data, performs CRUD operations, validates requests, returns appropriate HTTP status codes, and follows REST architecture principles.

Objectives

- Create API endpoints using GET, POST, PUT, and DELETE methods.
- Handle user requests and server responses.
- Validate input data.
- Return proper HTTP status codes.
- Implement basic security and error handling.

Technologies Used

- Node.js
- Express.js
- Postman
- JSON

Project Structure

backend-api/
├── server.js
├── routes/
│   └── users.js
├── controllers/
├── middleware/
├── package.json
└── README.md

API Endpoints

GET /users

Returns all users.

GET /users/:id

Returns a specific user by ID.

POST /users

Creates a new user.

PUT /users/:id

Updates user information.

DELETE /users/:id

Deletes a user.

Sample JSON Data

{
  "id": 101,
  "name": "John Doe",
  "email": "john@example.com"
}

HTTP Status Codes Used

- 200 OK
- 201 Created
- 204 No Content
- 400 Bad Request
- 401 Unauthorized
- 403 Forbidden
- 404 Not Found
- 429 Too Many Requests
- 500 Internal Server Error

Features

- RESTful API architecture
- CRUD operations
- JSON data exchange
- Input validation
- Error handling
- Security best practices

Testing

API endpoints were tested using Postman to verify functionality and response codes.

Conclusion

This project helped me understand backend development concepts, API design, request-response handling, validation, and server-side logic. It serves as a foundation for building scalable full-stack applications.



