# Meesho Clone Backend

This is the backend for the Meesho Clone project, built using Node.js, Express.js, MongoDB, and JWT for user authentication.


API DOCUMENTATION LINK : https://documenter.getpostman.com/view/36698863/2sAXxMgYvW

BACKEND LINK :  https://meesho-backend-xefg.onrender.com

## Features

- **User Authentication**: Signup, login, and logout functionalities using JWT.
- **Product Management**: products endpoint 
- **Cart Functionality**: Add, remove, and manage items in the shopping cart.
- **Secure API Endpoints**: JWT-based token authentication to secure routes.
- **API Documentation**: Postman collection for easy testing.

## Technologies Used

- **Node.js**: JavaScript runtime used to build the server-side application.
- **Express.js**: Web framework for building APIs.
- **MongoDB**: NoSQL database for storing product and user information.
- **Mongoose**: ODM library for MongoDB.
- **JWT (JSON Web Token)**: Used for user authentication and authorization.
- **Axios**: Used in the frontend to make API requests.


### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/sreeramss/Meesho-clone-Fullstack
    ```

2. Navigate into the project directory:
    ```bash
    cd backend
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

4. Create a `.env` file in the root directory and add the following environment variables:
    ```env
    PORT=8080
    MONGO_URI=<your_mongo_db_connection_string>
    JWT_SECRET_KEY=<your_jwt_secret>
    CORS_ORIGIN="Your Frontend link "
    ```

5. Start the development server:
    ```bash
    npm run dev
    ```


