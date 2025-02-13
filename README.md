# Chat App with Node.js and Frontend using HTML & JavaScript


# Chat App with Node.js and Frontend using HTML & JavaScript

## Overview
This project is a real-time chat application built using **Node.js** on the backend and **HTML**, **JavaScript** on the frontend. The application allows users to create and join different chat rooms based on subjects. Teachers act as administrators, while students can join rooms, share content, and discuss topics.

## Features
- **User Authentication**: Teachers and students login with unique credentials.
- **Separate Chat Rooms**: Chat rooms for different subjects (e.g., Math, Science, History).
- **Teacher as Admin**: Teachers can create, moderate, and manage chat rooms.
- **Real-time Messaging**: Messages are sent and received in real-time using **Socket.IO**.
- **File Sharing**: Users can share files (documents, images, etc.).
- **Message History**: Stores previous conversations for reference.

## Tech Stack
### Backend
- **Node.js** (server-side runtime)
- **Express.js** (web framework for handling requests)
- **Socket.IO** (real-time communication)
- **MongoDB** (database for storing user data and messages)

### Frontend
- **HTML/CSS/JavaScript** (UI and client-side scripting)
- **Socket.IO-client** (for real-time updates)

## Installation
### Prerequisites
Ensure you have the following installed:
- **Node.js** (https://nodejs.org/)
- **MongoDB** (https://www.mongodb.com/)
- **Git** (optional, for version control)

### Steps to Setup
1. **Clone the repository**
   ```sh
   git clone https://github.com/ArleneDcosta/Chat-Application.git
   cd Chat-Application
   ```
2. **Install dependencies**
   ```sh
   npm install
   ```
3. **Start MongoDB (if running locally)**
   ```sh
   mongod
   ```
4. **Start the backend server**
   ```sh
   npm start
   ```
5. **Open `index.html` in your browser**

## Project Structure
```bash
chat-app/
│── server.js           # Main server file
│── package.json        # Dependencies and scripts
│── public/             # Frontend assets
│   ├── index.html      # Main chat UI
│   ├── style.css       # Styling
│   ├── script.js       # Frontend logic
│── models/             # Database schemas
│── routes/             # API endpoints
│── config/             # Configuration files
│── sockets/            # Socket.IO logic
```

## Usage
- Teachers create chat rooms for different subjects.
- Students join rooms and participate in discussions.
- Real-time updates ensure smooth messaging.
- Admins can moderate chat rooms (e.g., remove users, delete messages).

## Future Enhancements
- Video and Audio Chat Integration
- Notifications & Mentions
- Advanced User Roles (e.g., moderators)
- Mobile-friendly UI
- Online presence

## Contributing
1. Fork the repository
2. Create a new branch (`feature-xyz`)
3. Commit changes
4. Push and create a pull request

---
Happy coding! 🚀
