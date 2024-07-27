# Goal Setter App

## Overview
The Goal Setter App is a full stack web application built using the MERN stack (MongoDB, ExpressJS, ReactJS, and Node.js). It allows users to set, manage, and track their goals. The app includes user authentication using JSON Web Tokens (JWT) to ensure secure access to user data.

## Features
- **User Authentication**: Register and login using JWT for secure access.
- **Goal Management**: Create, update, and delete personal goals.
- **User Dashboard**: View and manage goals in a user-specific dashboard.
- **Responsive Design**: Optimized for both desktop and mobile use.

## Technologies Used
- **Frontend**: ReactJS, HTML, CSS, JavaScript
- **Backend**: Node.js, ExpressJS
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **Version Control**: Git

## Getting Started

### Prerequisites
- Node.js installed
- MongoDB installed and running
- Git installed

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/goal-setter-app.git
    cd goal-setter-app
    ```

2. **Install server dependencies:**
    ```bash
    cd server
    npm install
    ```

3. **Install client dependencies:**
    ```bash
    cd ../client
    npm install
    ```

### Environment Variables
Create a `.env` file in the root directory of the `server` folder and add the following environment variables:
MONGO_URI=<Your MongoDB URI>
JWT_SECRET=<Your JWT Secret>

### Running the Application

1. **Start the server:**
    ```bash
    cd server
    npm start
    ```

2. **Start the client:**
    ```bash
    cd ../client
    npm start
    ```

3. Open your browser and go to `http://localhost:3000` to view the application.

## Folder Structure

goal-setter-app/
│
├── client/ # React frontend
│ ├── public/
│ └── src/
│ ├── components/
│ ├── pages/
│ ├── App.js
│ └── index.js
│
├── server/ # Express backend
│ ├── config/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ └── server.js
│
├── .gitignore
├── package.json
├── README.md
└── .env.example

## Key Endpoints

- **User Authentication:**
  - `POST /api/users/register` - Register a new user
  - `POST /api/users/login` - Login an existing user

- **Goal Management:**
  - `GET /api/goals` - Get all goals for a user
  - `POST /api/goals` - Create a new goal
  - `PUT /api/goals/:id` - Update a goal
  - `DELETE /api/goals/:id` - Delete a goal

## Contributing
Feel free to submit issues and pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License.

## Contact
- **Author**: Muhammad Taha
- **GitHub**: [https://github.com/raja-taha](https://github.com/raja-taha)
- **Email**: [rajataha062@gmail.com](mailto:rajataha062@gmail.com)
