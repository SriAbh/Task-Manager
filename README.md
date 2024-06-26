Task-Manager MERN App Setup
To run the Task-Manager app, follow these steps:

Step 1: Clone the Repository
Clone the Git repository to your local system:

git clone <repository_url>


Step 2: Navigate to the Frontend Directory
After cloning, you will have two directories: backend and frontend. Move to the frontend directory:

cd frontend

Step 3: Install Frontend Dependencies
Install necessary libraries, including concurrently, in the frontend directory:

npm install concurrently

Step 4: Install Backend Dependencies
Move out of the frontend directory and navigate to the backend directory to install mongoose:

cd ..
cd backend
npm install mongoose

Step 5: Return to the Frontend Directory
Go back to the frontend directory:

cd ..
cd frontend

Step 6: Run the App
Run the following command to start the app:

npm run dev


The app will be live on your local system.

Note
If the app does not run and throws errors related to missing libraries, install the required libraries as indicated.

Important
Ensure you have all necessary setups installed on your system, such as MongoDB, Node.js, etc.
