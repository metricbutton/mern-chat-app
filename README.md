# Chat App

## Description
A real-time messaging application.

## Features

### User Authentication
- **Authentication and authorization** using **JSON Web Tokens (JWT)**.
- Users can sign up, log in, and access protected routes.
- JWT tokens are used for secure communication between the client and server.

### Real-Time Messaging
- **Socket.io** enables real-time messaging.
- Users can send and receive messages instantly.
- The chat interface updates dynamically as new messages arrive.

### Online User Status
- **Socket.io** tracks online user status.
- Users are notified when others come online or go offline.

### State Management
- Global state management with **Zustand**
