
# Project Title

A brief description of what this project does and who it's for

Blog Platform

A fully functional blog platform that allows users to create, read, update, and delete posts. Built using React for the frontend and Node.js with MongoDB for the backend.
Table of Contents

    Features
    Prerequisites
    Installation
        Frontend Setup
        Backend Setup
    Environment Variables
    Usage
    License

Features

    User Authentication using JWT.
    Create, Read, Update, and Delete (CRUD) operations for blog posts.
    Fully responsive UI.
    MongoDB for efficient data storage.
    Secure backend with environment variables.

Prerequisites

Before starting, ensure you have the following installed:

    Node.js and npm
    MongoDB (Local or Atlas account)

Installation
Frontend Setup

    Clone the Frontend Repository

git clone https://github.com/VaibhavPuri26/Blog-Platform.git

Navigate to the Project Directory

cd client

Install Dependencies

npm install

Set Up Environment Variables

    Create a .env file in the root of the frontend directory.
    Add the following variable:

    REACT_APP_API_URL=http://localhost:5000/api

    Replace http://localhost:5000/api with your backend API URL if hosted elsewhere.

Start the Development Server

    npm start

    The frontend should now be running at http://localhost:3000.

Backend Setup

    Clone the Backend Repository

git clone https://github.com/VaibhavPuri26/Blog-Platform.git

Navigate to the Backend Directory

cd api

Install Dependencies

npm install

Set Up Environment Variables

    Create a .env file in the backend directory.
    Add the following variables:

    PORT=9080
    MONGO_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret

    Replace your_mongodb_uri with your MongoDB connection string and your_jwt_secret with a secure key for signing JSON Web Tokens.

Start the Server

    npm start

    The backend should now be running at http://localhost:5000 (or the port you specified).

Environment Variables

Ensure the following environment variables are set up correctly:

Frontend .env File

REACT_APP_API_URL=http://localhost:5000/api

Backend .env File

PORT=9080
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret

Usage

    Start the backend server as described in the backend setup section.
    Start the frontend development server as described in the frontend setup section.
    Open your browser and navigate to http://localhost:3000 to start using the platform.
