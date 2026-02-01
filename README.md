# Car Rental Full Stack Web Application

## Overview
A full-stack car rental web application that allows users to browse available cars, upload images, and manage bookings.  
The application follows a client–server architecture with secure environment-based configuration.

## Tech Stack
- Frontend: JavaScript, Vite
- Backend: Node.js, Express
- Database: MongoDB (Atlas)
- Image Storage: ImageKit
- Tools: Git, GitHub, VS Code

## Features
- Client–server separation
- Image upload using ImageKit
- Environment-based configuration
- Scalable folder structure

## Prerequisites
- Node.js installed
- MongoDB Atlas account
- ImageKit account

## Environment Setup

### Server (`/server`)
Create a `.env` file inside the `server` folder and add:

MONGO_URI=your_mongodb_connection_string
PUBLIC_KEY=your_imagekit_public_key
PRIVATE_KEY=your_imagekit_private_key
URL_ENDPOINT=your_imagekit_url_endpoint

### Client (`/client`)
No environment variables required.

## How to Run Locally

### 1️⃣ Start the Server
```bash
cd server
npm install
npm run server

2️⃣ Start the Client
cd client
npm install
npm run dev

The application will run locally once both server and client are active.

