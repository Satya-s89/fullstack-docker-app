# Fullstack Docker App

This project is a full-stack application that utilizes a React frontend, an Express backend, and a PostgreSQL database. The application is structured to facilitate development and deployment using Docker.

## Project Structure

```
fullstack-docker-app
├── backend
│   ├── app.js          # Main entry point for the Express backend
│   └── package.json    # Configuration file for the backend Node.js application
├── frontend
│   ├── package.json    # Configuration file for the React frontend application
│   └── src
│       └── App.js      # Main component of the React application
├── db-data             # Empty folder for PostgreSQL database volume
├── docker-compose.yml   # File to define and run multi-container Docker applications
├── .env                # File for environment variables (to be used in the future)
└── README.md           # Documentation for the project
```

## Backend

The backend is built using Node.js and Express. It connects to a PostgreSQL database and exposes a simple API endpoint that returns the current server time.

### Setup

1. Navigate to the `backend` directory.
2. Install dependencies using `npm install`.
3. Start the server with `npm start`.

## Frontend

The frontend is built using React. It fetches data from the backend API and displays it to the user.

### Setup

1. Navigate to the `frontend` directory.
2. Install dependencies using `npm install`.
3. Start the application with `npm start`.

## Database

The `db-data` folder is intended for use as a volume for the PostgreSQL database. This allows for persistent data storage.

## Docker

The project includes a `docker-compose.yml` file for managing multi-container Docker applications. This file is currently empty and can be configured in the future to define services for the backend, frontend, and database.

## Environment Variables

The `.env` file is included for future use to manage environment variables securely.

## Contribution

Feel free to contribute to this project by forking the repository and submitting a pull request.