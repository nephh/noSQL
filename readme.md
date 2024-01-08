# Social Media API

A simple API for an example social media platform using MongoDB.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
    - [User routes](#user-routes)
    - [Thought routes](#thought-routes)
- [License](#license)

## Features

- User creation, retrieval, update, and deletion
- Thought (post) creation, retrieval, update, and deletion
- Reaction (comment) creation and deletion on thoughts
- Add and remove friends for a user

## Installation

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run `npm install` to install all dependencies.

## Usage

1. Start the server by running `npm start`.
2. Use a tool like Postman or Insomnia to make requests to the API.

## API Endpoints

### User routes:

- GET, POST: `/api/users`
- GET, PUT, DELETE: `/api/users/:userId`
- POST, DELETE: `/api/users/:userId/friends/:friendId`

### Thought routes:

- GET, POST: `/api/thoughts`
- GET, PUT, DELETE: `/api/thoughts/:thoughtId`
- POST, DELETE: `/api/thoughts/:thoughtId/reactions`

## License

This project is licensed under the terms of the MIT license.
