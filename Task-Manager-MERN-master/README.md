# Task Coordinator - A MERN Stack Application Project

![Taskmaster](https://res.cloudinary.com/dpreiehu7/image/upload/v1755023743/task_coordinator_pwwi9b.png)

## Project Description

A full-stack web application called Taskmanager/ a task coordinator was created to assist users in effectively managing their tasks.  This application, which was developed using the MERN stack (MongoDB, Express.js, React.js, and Node.js), enables users to create, update, delete, mark tasks as finished, register, and log in.  Users can also search for tasks by name and filter them by state (completed or pending).

## Features

- Account Creation and Sign-In
- Add, Modify, and Remove Tasks
- Designate Tasks as Finished
- Sort Tasks by Status (Done, Ongoing)
- Look for Tasks by Title
- Adaptable and Easy-to-Use Interface
- Authentication using JWT

## Live Demo

Check out the live demo: [Taskmaster Live Demo](https://task-manager-git-main-tanishas-projects-95c990ac.vercel.app/)

## Local Installation Guide

Follow these steps to set up the project locally:

### Clone the Repository

1. Clone the repository:
   ```bash
   git clone https://github.com/TANISHA0404/Task-Manager.git
   cd Task-Manager-MERN
   ```

### Front-end

1. Navigate to the client directory:
   ```bash
   cd client
   ```
2. Install the dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

### Back-end

1. Navigate to the server directory:
   ```bash
   cd server
   ```
2. Install the dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

### Environment Variables

Create a `.env` file in the server directory with the following variables:

```
MONGO_USER=your_mongodb_user
MONGO_PASS=your_mongodb_password
JWT_SECRET=your_jwt_secret
COOKIE_DOMAIN=localhost_or_your_server_domain
ISPRODUCTION=false_or_true
COOKIE_EXPIRE=86400000
```

Create a `.env.local` file in the client directory with the following variable:

```
VITE_SERVER_URL=your_server_url
```

## Docker Installation Guide

To run the project using Docker, follow these steps:

1. Ensure you have Docker and Docker Compose installed on your machine.
2. In the root directory of the project, run the following command:
   ```bash
   docker-compose -f ./docker-compose.yaml up
   ```
3. Docker will build the images and start the containers for both the client and server.

## Contribution

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch with a descriptive name.
3. Make your changes and commit them with clear and concise messages.
4. Push your changes to your forked repository.
5. Create a pull request to the main repository.

