# share-places-app - Backend

This is the backend server for the Project 'share-places' application, built using Node.js and Express.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js installed
- MongoDB installed and running

## Getting Started

To install the required dependencies, run:

- terminal
  npm install

## API Endpoints

### Users:

- GET /api/users: Get all Users.
- POST /api/users/signup: Signup new user.
- POST /api/users/login: Login user.

### Places:

- GET /api/places/user/:userId: Get places by creator user ID.
- GET /api/places/:placeId: Get a specific place by ID.
- POST /api/places: Create a new place.
- PATCH /api/places/:placeId: Update a place by ID.
- DELETE /api/places/:placeId: Delete a place by ID.
