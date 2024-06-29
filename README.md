
# Book Search Engine

## Description

A Google Books API search engine built with the MERN stack, refactored to use a GraphQL API with Apollo Server. The application allows users to search for books and save them to their account.

## Installation

To install and run the application locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/StgoWF/book-search-graphql.git
   ```

2. Navigate to the project directory:

   ```bash
   cd YOUR_REPOSITORY_NAME
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Set up the environment variables. Create a `.env` file in the root directory and add the following:

   ```
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   ```

5. Start the server:

   ```bash
   npm start
   ```

6. Open your browser and go to `http://localhost:3000`.

## Deployment

The application is deployed on Render. You can access the live application at:

[https://your-app-name.onrender.com](https://your-app-name.onrender.com)

## Technologies Used

- React
- Node.js
- Express.js
- MongoDB
- Apollo Server
- GraphQL

## Features

- Search for books using the Google Books API
- Save books to your account
- View saved books
- Remove books from your saved list

## License

This project is licensed under the MIT License.
