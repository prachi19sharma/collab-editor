# Real-Time Collaborative Code Editor

## Overview

This is a real-time collaborative code editor built using Node.js, Express, and Socket.IO. It allows multiple users to write and edit code together in a shared environment. The changes reflect live across all connected users, making it useful for collaborative coding sessions, interviews, or group learning.

## Live Link

https://collab-editor-yq7p.onrender.com/

## Features

- Real-time code syncing using WebSockets
- Multi-user collaborative editing
- Simple and minimal frontend interface
- Lightweight and fast Node.js backend
- Hosted and accessible online

## Tech Stack

- Frontend: HTML, CSS, JavaScript
- Backend: Node.js, Express
- Real-time Communication: Socket.IO
- Hosting: Render

## How it Works

1. The server uses Express and Socket.IO to manage real-time connections.
2. When a user types in the editor, their input is sent to the server.
3. The server broadcasts this data to all connected clients.
4. Every client updates the editor in real-time with the latest changes.

## Run Locally

```bash
git clone https://github.com/prachi19sharma/collab-editor.git
cd collab-editor
npm install
node server.js
```

Visit `http://localhost:3000` in your browser.

## Folder Structure

```
collab-editor/
├── public/             # Static frontend files
├── server.js           # Main server file
├── package.json        # Project metadata and dependencies
└── .gitignore          # Ignoring node_modules, etc.
```

## Author

Prachi Sharma  
GitHub: https://github.com/prachi19sharma
