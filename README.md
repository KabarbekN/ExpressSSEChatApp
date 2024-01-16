# MyChat - Real-Time Chat Application

MyChat is a real-time chat application developed using Node.js and Express on the server side, and HTML/JavaScript on the client side. It enables users to send and receive messages in real-time.

## Features

- **/sse Endpoint:** Establishes a Server-Sent Events (SSE) connection to receive messages in real-time.
- **/chat Endpoint:** Allows users to send messages to the server.
- **/echo Endpoint:** Echoes back the input query parameter in various formats.
- **/static/* Endpoint:** Serves static files from the "mychat" directory.
- **/json Endpoint:** Responds with a JSON object.
- **/ Endpoint:** Responds with a simple text message.
- **/chatpage Endpoint:** Directly accesses the chat interface.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/mychat.git
   cd mychat
Install dependencies:

bash
Copy code
npm install
Run the server:

bash
Copy code
npm start
Open your browser and navigate to http://localhost:3000/chatpage to access MyChat.

Usage
Open the chat interface by visiting http://localhost:3000/chatpage.
Enter your messages and enjoy real-time communication.
