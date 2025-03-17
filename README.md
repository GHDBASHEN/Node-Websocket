# Node.js WebSocket Chat

A real-time chat application built with **Node.js**, **Express.js**, and **WebSockets**.

## Features
- Real-time messaging using WebSockets
- Stores chat messages and sends them to new clients on connection
- Uses **EJS** for templating
- Serves static assets
- CORS enabled for cross-origin requests

![{96A4BD9E-9610-420E-BC68-513FD53B9ABD}](https://github.com/user-attachments/assets/b51cad05-b88d-4ec1-9b2b-ed6bb0cb2d0d)

## Installation

### Prerequisites
Ensure you have **Node.js** installed on your system.

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/GHDBASHEN/node-websocket.git
   cd node-websocket
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the server:
   ```sh
   npm start
   ```
   The Express server will run on `http://localhost:3000` and the WebSocket server on `ws://localhost:3001`.

## Configuration
You can customize the server settings using environment variables:

| Variable  | Description                         | Default |
|-----------|-------------------------------------|---------|
| `PORT`    | HTTP server port                   | `3000`  |
| `WSPORT`  | WebSocket server port              | `3001`  |
| `NAMELEN` | Maximum length for usernames       | `15`    |
| `MSGLEN`  | Maximum length for chat messages   | `200`   |

## Project Structure
```
node-websocket-chat/
├── views/              # EJS templates
├── static/             # Static assets (CSS, JS, images)
├── index.js           # Main Express and WebSocket server
├── package.json        # Project dependencies and scripts
└── README.md           # Project documentation
```

## Usage
- Open `http://localhost:3000` in your browser.
- Send and receive messages in real-time.

## License
This project is licensed under the MIT License.
