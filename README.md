# K-Media: Social Media Platform Backend

Welcome to the K-Media Social Media Platform backend repository. This project is a backend implementation for a social media platform built using Node.js, Express.js, and MongoDB. The backend handles user authentication, profile management, and post creation.

## Features

- **User Authentication**: Sign up, login, and secure your account using JWT tokens.
- **User Profiles**: Create and manage user profiles with personal details.
- **Posts**: Create, edit, and delete posts.

## Tech Stack

- **Node.js**: JavaScript runtime for building server-side applications.
- **Express.js**: Web framework for building APIs.
- **MongoDB**: NoSQL database for storing user data and posts.
- **Mongoose**: ODM for MongoDB to interact with the database easily.
- **JWT**: JSON Web Tokens for secure authentication.

## Installation

To set up this project locally, follow these steps:

1. **Clone the repository and navigate to the project directory:**

   ```bash
   git clone https://github.com/Kanishk-Chaudhary/K-Media.git && cd K-Media
   ```

2. **Install the dependencies:**

   ```bash
   npm install
   ```

3. **Create a `.env` file in the root directory and add the following environment variables:**

   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

4. **Start the development server:**

   ```bash
   npm run start
   ```

5. The server will run on `http://localhost:5000`.

## API Endpoints

### User Authentication

- **POST /api/users/signup**: Register a new user.
- **POST /api/users/login**: Authenticate user and return a JWT token.

### User Profile

- **GET /api/profile/:**: Get the logged-in user's profile.
- **POST /api/profile**: Create or update a user profile.

### Posts

- **POST /api/posts**: Create a new post.
- **GET /api/posts/:id**: Get all posts.
- **DELETE /api/posts/:id**: Delete a post by ID.

## Thank You
