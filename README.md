Task Manager
Getting Started
Follow these steps to set up and run the Task Manager project on your local machine.

Prerequisites
Node.js (Ensure it's installed on your system)
MongoDB (For the database)
Git (For cloning the repository)


Installation:

Clone the Repository
git clone <url>
cd <project name>

Install Dependencies
Navigate to the backend and frontend directories and install the necessary dependencies:

# In the backend directory
cd backend
npm install

# Install nodemon for backend
npm install nodemon

# In the frontend directory
cd ../frontend
npm install
Configure Environment Variables

Add your personalized MongoDB key to the .env file in the backend directory:

# .env file
MONGODB_URI=your_mongodb_key
Running the Project
Start the Backend Server

In the backend directory, start the server using nodemon:

cd backend
nodemon app.js
Start the Frontend Server

In the frontend directory, start the client server:

cd frontend
npm start
Alternatively, you can use Vite:

npm run dev
You're All Set!
Your Task Manager project should now be running successfully.
