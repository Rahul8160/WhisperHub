WhisperHub
WhisperHub is a real-time chat application built with the MERN stack and WebSocket technology. It allows users to communicate instantly with each other in a seamless and efficient manner.

Features
Real-time messaging: Instant messaging capabilities using WebSocket for a responsive chat experience.
User authentication: Secure login and registration using JWT (JSON Web Tokens) for authentication.
File uploads: Ability to send and receive files within chat messages.
User profiles: View and update user profiles with customizable avatars.
Online status: Shows online status of users in real-time.
Technologies Used
Frontend: React.js, WebSocket (Socket.IO), Axios
Backend: Node.js, Express.js, WebSocket (Socket.IO), MongoDB (Mongoose)
Authentication: JSON Web Tokens (JWT), bcryptjs for password hashing
File Storage: Local storage (uploads) for storing uploaded files
Getting Started
Prerequisites
Node.js installed on your machine
MongoDB Atlas account (or local MongoDB server) for database storage
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/Rahul8160/whisperhub.git
cd whisperhub
Install dependencies for both frontend and backend:

bash
Copy code

# Install server dependencies

cd server
npm install

# Install client dependencies

cd ../client
npm install
Set up environment variables:

Create a .env file in the api directory with the following variables:

plaintext
Copy code
PORT=4040
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CORS_ORIGIN=http://localhost:5173 # Adjust according to your frontend URL
ALLOW_CREDENTIALS=true
Replace your_mongodb_connection_string with your MongoDB connection string and your_jwt_secret with your JWT secret key.

Run the application:

bash
Copy code

# Start the server (from the server directory)

cd ../server
npm start

# Start the client (from the client directory)

cd ../client
npm start
Access the application:

Open your browser and go to http://localhost:5173 to use WhisperHub.

Usage
Register an account or log in if you already have one.
Start chatting with other users in real-time.
Upload files by clicking on the file icon in the chat input field.
View and update your profile information.
Contributing
Contributions are welcome! Please fork the repository and create a pull request with your improvements.
