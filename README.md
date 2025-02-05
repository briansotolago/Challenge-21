# MERN: Google Books Search

## Description

This project is a book search engine application built using the MERN stack (MongoDB, Express.js, React, Node.js). The application allows users to search for books using the Google Books API and save their favorite books to a personal list. The application has been refactored to use GraphQL with Apollo Server, replacing the previous RESTful API.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Deployment](#deployment)
- [Repo](#repo)
- [License](#license)

## Installation

1. Clone the repository:
        ```bash
   git clone <repository-url>
         ```
2. Navigate to the project directory:
        ```bash
   cd google-books-search
        ```
3. Install dependencies:
        ```bash
   npm install
        ```

## Usage

1. Start the server:
                  ```bash
   npm run develop
                  ```
2. Open your browser and navigate to `http://localhost:3000` to access the application.

## Features

- **Search for Books**: Users can search for books using the Google Books API.
- **User Authentication**: Users can sign up and log in to save their favorite books.
- **Save Books**: Logged-in users can save books to their personal list.
- **View Saved Books**: Users can view and manage their saved books.
- **GraphQL API**: The application uses GraphQL with Apollo Server for data fetching and mutations.

## Technologies Used

- **MongoDB**: Database for storing user and book data.
- **Express.js**: Web framework for Node.js.
- **React**: Front-end library for building user interfaces.
- **Node.js**: JavaScript runtime for the server.
- **Apollo Server**: GraphQL server for handling API requests.
- **GraphQL**: Query language for APIs.

## Deployment

The application is deployed on Render with a MongoDB database hosted on MongoDB Atlas. You can access the live application at [Live URL](https://challenge-21-jwej.onrender.com).

## Repo

[GitHub Repo](https://github.com/briansotolago/Google_Books_Search)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please contact [Brian Soto](briansoto.bs23@gmail.com).
