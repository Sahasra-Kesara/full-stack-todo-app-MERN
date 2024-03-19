# MERN-TO-DO-APP
### Project Overview:
This project is a Todo App built using the MERN stack. It includes both frontend and backend components to manage tasks efficiently.

### Features:
- Add new todos to the list
- Delete todos from the list
- Edit todos from the list

### Setup Instructions:
1. Clone the repository.
2. Navigate to the frontend folder and run `npm install` to install frontend dependencies.
3. Start the frontend server by running `npm start`.
4. Navigate to the backend folder and run `npm install` to install backend dependencies.
5. Start the backend server by running `node server.js`.

### Dependencies:
```json
{
  "dependencies": {
    "cors": "^2.8.5",
    "dotenv": "^16.3.1",
    "env": "^0.0.2",
    "express": "^4.18.2",
    "mongoose": "^7.3.4",
    "nodemon": "^3.0.1"
  }
}

MongoDB Connection Options:
plaintext
MONGO_URI = mongodb+srv:<username>:<password>@cluster0.i2qpuhb.mongodb.net/kesaradb?retryWrites=true&w=majority&appName=Cluster0

Connecting to MongoDB:
When setting up the MongoDB connection, replace <username> with your MongoDB username and <password> with your MongoDB password.
Additional Notes:
Make sure both frontend and backend servers are running concurrently for full functionality.

This README.md template provides a structured guide for users to understand the project, set it up, and interact with it effectively.

