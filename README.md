# ChatApp

Welcome to ChatApp, a real-time chat application that provides users with a seamless platform for communication. Built with modern technologies, ChatApp offers a secure and efficient way for users to connect with each other.

## Description

ChatApp is a real-time messaging application developed using the MERN stack (MongoDB, Express.js, React.js, Node.js). It utilizes Socket.io for real-time communication, ensuring instant message delivery between users. User authentication is implemented with JWT (JSON Web Tokens) and bcryptjs for password hashing, ensuring secure access to the platform.

## Tech Stack

- **Frontend:**
  - React.js
  - Tailwind CSS

- **Backend:**
  - Node.js
  - Express.js

- **Database:**
  - MongoDB

- **Authentication:**
  - JSON Web Tokens (JWT)
  - bcryptjs

- **Real-Time Communication:**
  - Socket.io

## Features

- **User Authentication:**
  - Secure sign up and log in functionality.
  - Passwords are hashed for enhanced security.

- **Real-Time Messaging:**
  - Instant messaging between users in real-time.
  - Responsive and intuitive chat interface.

- **User Profile:**
  - Personalized user profiles with avatars based on gender.
  - Option to update profile information.

- **Conversations:**
  - List of ongoing conversations with real-time updates.
  - Send and receive messages instantly.

## Future Scope

- **Enhanced Security:**
  - Implement email OTP verification for user registration.
  - Introduce end-to-end encryption for user chats.

- **Group Chats:**
  - Allow users to create group chats and add or remove members.
  - Implement admin controls for group chat management.

- **Additional Features:**
  - Introduce a "forgot password" feature for users to reset their passwords.
  - Implement multimedia file sharing capabilities within chats (images, videos, documents).

## Deployment

This application is deployed on [Render.com](https://render.com). You can access the live version of the app [here](https://chat-app-7bfs.onrender.com).

## Environment Variables

The `.env` file contains the following environment variables:
 ```js
 MONGO_URI=your_mongodb_connection_string 
 JWT_SECRET=your_jwt_secret_key 
 PORT=5000
```


## Installation

To run this project locally, follow these steps:

1. Clone the repository:
 ```shell
 git clone https://github.com/Jayashankar-K/Chat-App 
 cd chatapp
```

2. Install backend dependencies:
 ```shell
 npm install
``` 

3. Install frontend dependencies:
 ```shell
 cd frontend 
 npm install 
 cd ..
```

4. Run the application:
 ```shell
 npm run server
```

5. Build the frontend:
 ```shell
 npm run build
```

6. Start the application:
 ```shell
 npm start
``` 


## Acknowledgements

Special thanks to the developers and contributors of the libraries and tools used in this project.

