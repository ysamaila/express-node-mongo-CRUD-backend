# Express Node MongoDB CRUD Backend

![Node.js](https://img.shields.io/badge/Node.js-14.x%20%7C%2016.x%20%7C%2018.x-green)
![Express](https://img.shields.io/badge/Express-4.x-red)
![MongoDB](https://img.shields.io/badge/MongoDB-4.x%20%7C%205.x%20%7C%206.x-blue)

This repository contains a simple CRUD (Create, Read, Update, Delete) backend application built with Node.js, Express.js, and MongoDB. It serves as a basic template for building RESTful APIs using these technologies. It also features authentication using the JWT technology.

## Features

- **Create**: Create new records in the MongoDB database.
- **Read**: Retrieve existing records from the database.
- **Update**: Update records in the database.
- **Delete**: Delete records from the database.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/ysamaila/express-node-mongo-CRUD-backend.git
   ```

2. Install the project dependencies:

   ```bash
   cd express-node-mongo-CRUD-backend
   npm install
   ```

3. Start the application:

   ```bash
   npm start
   ```

   This will start the server at `http://localhost:3000`.

## API Endpoints

- **GET /api/stuff**: Retrieve all items from the database.
- **GET /api/stuff/:id**: Retrieve a specific item by ID.
- **POST /api/stuff**: Create a new item.
- **PUT /api/stuff/:id**: Update a specific item by ID.
- **DELETE /api/stuff/:id**: Delete a specific item by ID.

- **GET /api/auth/login**: Allow user to login after credentials are authenticated.
- **GET /api/auth/signup**: Allow user to sign up after verifying that user does not exist.

## Project Structure

- `server.js`: The main entry point for the application.
- `routes/`: Defines the API routes and their corresponding controller methods.
- `controllers/`: Contains the logic for handling API requests.
- `models/`: Defines the MongoDB schema for items.
- `app.js`: Defines all the middlewares used by the application.
- `server.js`: Defines the server details.

## Dependencies

- **Express**: Fast, unopinionated, minimalist web framework for Node.js.
- **Mongoose**: MongoDB object modeling for Node.js.
- **dotenv**: Loads environment variables from a `.env` file.
- **body-parser**: Middleware to parse request bodies.
- **morgan**: HTTP request logger middleware.
- **cors**: Middleware for enabling Cross-Origin Resource Sharing (CORS).
- **jsonwebtoken**: Efficient package that enables the implementation of JWT authentication.

## Core Team

**Yusuf Samaila**

-[on LinkedIn](https://www.linkedin.com/in/yusufsd) -[on Twitter](https://twitter.com/ysamaila_)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Happy coding! 🚀
