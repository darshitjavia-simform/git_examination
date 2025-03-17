# MERN Stack Project

This is a simple MERN (MongoDB, Express, React, Node.js) stack project structured with separate frontend and backend directories. The project is designed to demonstrate a full-stack application using the MERN stack.

## Project Structure

```
mern-project
├── frontend
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── services
│   │   ├── utils
│   │   ├── App.js
│   │   └── index.js
│   ├── public
│   ├── package.json
│   └── .env.sample
├── backend
│   ├── src
│   │   ├── controllers
│   │   ├── models
│   │   ├── routes
│   │   ├── middleware
│   │   ├── config
│   │   └── app.js
│   ├── package.json
│   └── .env.sample
├── package.json
└── README.md
```

## Getting Started

### Prerequisites

- Node.js
- MongoDB

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd mern-project
   ```

2. Install dependencies for the frontend:
   ```bash
   cd frontend
   npm install
   ```

3. Install dependencies for the backend:
   ```bash
   cd ../backend
   npm install
   ```

### Environment Variables

Create a `.env` file in both the `frontend` and `backend` directories based on the provided `.env.sample` files.

### Running the Application

1. Start the backend server:
   ```bash
   cd backend
   npm start
   ```

2. Start the frontend application:
   ```bash
   cd frontend
   npm start
   ```

### Features

- RESTful API built with Express and MongoDB.
- React frontend with routing and component structure.
- Sample environment variable configurations.

### Contributing

Feel free to fork the repository and submit pull requests for any improvements or features.

### License

This project is licensed under the MIT License.