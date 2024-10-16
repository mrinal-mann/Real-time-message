# Real-time Chat Application

This is a simple chat application built using raw WebSockets in Node.js. It allows an admin to create chat rooms and manage them, while users can join rooms, send messages, and upvote chat messages. Messages with higher upvotes will be moved to separate sections, and admins will be alerted when specific conditions are met.

## Features

- **Users**
  - Join a chat room.
  - Send messages in the room.
  - Upvote messages.
  - Messages with more than 3 upvotes are moved to a separate section.
  - Messages with more than 10 upvotes trigger an alert to the admin.

## Requirements

- Node.js (v16.x or higher)
- npm (v7.x or higher)
- TypeScript

## Setup Instructions

### 1. Backend Setup

1. Open a terminal and navigate to the `backend` folder:
   ```bash
   cd backend
   ```
2. Compile the TypeScript code into JavaScript:
   ````bash
    npx tsc -b
3.Start the backend server:
    ```bash
    node dist/index.js

### 2. Frontend Setup

Open a new terminal and navigate to the frontend folder:

1. Navigate to the frontend folder
   ```bash
   cd frontend
   ```
2. Install the necessary dependencies:
   ```bash
   npm install
   ```
3. Start the frontend development server:
   ```bash
   npm run dev
### 3. Access the Application
Once both the backend and frontend servers are running, you can access the chat application through your browser at:

    ```http
    http://localhost:3000
    

## Demo Video

![screen-capture_2](https://github.com/user-attachments/assets/982218fb-9b4a-4538-94e6-e5ecbd8250ab)


