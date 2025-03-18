# MERN Stack Project

A full-stack application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack with a clean architecture and modern development practices.

## Tech Stack

- **Frontend:** React.js v18.2.0
- **Backend:** Node.js v18.x, Express.js v4.18.x
- **Database:** MongoDB v6.0+
- **Authentication:** JWT
- **State Management:** Redux Toolkit
- **API Documentation:** Swagger/OpenAPI

## Project Structure

```
frontend
   ├── src
   │   ├── components      # Reusable UI components
   │   ├── pages          # Page components
   │   ├── services       # API services
   │   ├── utils          # Utility functions
   │   ├── App.js
   │   └── index.js
   ├── public
   ├── package.json
   └── .env.sample
backend
   ├── src
   │   ├── controllers    # Route controllers
   │   ├── models        # Database models
   │   ├── routes        # API routes
   │   ├── middleware    # Custom middleware
   │   ├── config        # Configuration files
   │   └── app.js
   ├── package.json
   └── .env.sample
README.md
```

## Prerequisites

- Node.js (v18.x or higher)
- MongoDB (v6.0 or higher)
- npm (v9.x or higher) or yarn (v1.22.x or higher)

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd mern-project
   ```

2. Install frontend dependencies:
   ```bash
   cd frontend
   npm install
   ```

3. Install backend dependencies:
   ```bash
   cd ../backend
   npm install
   ```

## Environment Setup

### Backend (.env.sample)
```
NODE_ENV=development
PORT=5000
MONGODB_URI=mongodb://localhost:27017/your-database
JWT_SECRET=your-secret-key
JWT_EXPIRES_IN=7d
```

### Frontend (.env.sample)
```
REACT_APP_API_URL=http://localhost:5000/api
REACT_APP_ENV=development
```

## Running the Application

1. Start MongoDB service:
   ```bash
   sudo service mongod start
   ```

2. Start the backend server:
   ```bash
   cd backend
   npm run dev  # For development
   # or
   npm start    # For production
   ```

3. Start the frontend application:
   ```bash
   cd frontend
   npm start
   ```

The frontend will be available at `http://localhost:3000`
The backend API will be available at `http://localhost:5000`

## API Documentation

API documentation is available at `http://localhost:5000/api-docs` when running the backend server.

## Available Scripts

### Backend
- `npm start`: Starts the production server
- `npm run dev`: Starts the development server
- `npm test`: Runs the test suite
- `npm run lint`: Runs the linter

### Frontend
- `npm start`: Starts the development server
- `npm run build`: Builds the app for production
- `npm test`: Runs the test suite
- `npm run lint`: Runs the linter

