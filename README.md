# Car Rental Full Stack Web Application

## Overview
A full-stack car rental web application built using a client–server architecture.  
The application allows users to browse available cars and supports image uploads using a third-party image service.  
All sensitive configuration is handled securely using environment variables.

## Tech Stack
- Frontend: JavaScript, Vite
- Backend: Node.js, Express
- Database: MongoDB Atlas
- Image Storage: ImageKit
- Tools: Git, GitHub, VS Code

## Features
- Client–server architecture
- RESTful API using Express
- Image upload and management with ImageKit
- Secure environment-based configuration
- Scalable and organized project structure

## Prerequisites
- Node.js installed
- MongoDB Atlas account
- ImageKit account

## Environment Setup

### Server (`/server`)
Create a `.env` file inside the `server` folder and add the following:

```env
MONGO_URI=your_mongodb_connection_string
PUBLIC_KEY=your_imagekit_public_key
PRIVATE_KEY=your_imagekit_private_key
URL_ENDPOINT=your_imagekit_url_endpoint

Client (/client)

No environment variables are required for the client.

How to Run Locally
1️⃣ Start the Server
cd server
npm install
npm run server

2️⃣ Start the Client
cd client
npm install
npm run dev


Once both the server and client are running, the application will be available locally in your browser.
