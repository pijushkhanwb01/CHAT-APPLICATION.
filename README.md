# CHAT-APPLICATION.
#REAL-TIME-COLLABORATIVE-DOCUMENT-EDITOR #COMPANY: CODTECH IT SOLUTIONS #NAME:PIJUSH KHAN #INTERN ID:CT04DL1284 #DOMAIN:FULL STACK DEVELOPMENT #DURATION:4 WEEKS #MENTOR:NEELA SANTOSH
#about project Project Structure The project consists of the following files:

index.html: The main HTML file that defines the chat interface. It includes a message list and a form for sending messages.

style.css: Handles the visual styling of the chat app, including message bubbles, colors, and layout.

script.js: Manages client-side functionality, such as sending messages and displaying them in real time.

server.js: The backend server that handles WebSocket connections using Socket.IO and broadcasts messages to all connected clients.

package.json: Lists project dependencies, including Express and Socket.IO.

How It Works User Connection:

When a user opens the chat app in a browser, they connect to the server via Socket.IO.

The server logs the connection and assigns a unique ID to the user.

Sending Messages:

Users type messages into the input field and click "Send."

The message is sent to the server via Socket.IO.

The server broadcasts the message to all connected clients, including the sender.

Displaying Messages:

Messages appear in the chat window in real time.

Sent messages are styled differently (green bubble) from received messages (white bubble).

The chat automatically scrolls to show the latest message.

Disconnection:

If a user leaves, the server logs the disconnection.

Key Features Real-Time Updates: Messages appear instantly for all users without refreshing the page.

Simple UI: Clean design with responsive message bubbles.

User Identification: Each message shows who sent it (based on Socket.IO ID).

Auto-Scroll: The chat always stays at the latest message.

Technologies Used Node.js & Express: Handles the server-side logic.

Socket.IO: Enables real-time bidirectional communication.

HTML/CSS: Provides the structure and styling of the chat interface.

JavaScript: Powers the interactive features on the client side.

How to Run Install dependencies:

bash npm install Start the server:

bash node server.js Open the app in a browser: http://localhost:3000

Possible Improvements Add usernames instead of showing Socket.IO IDs.

Save chat history in a database.

Add private messaging between users.

Improve mobile responsiveness.

This project is a great starting point for learning real-time web applications with Socket.IO and Express. It demonstrates the core concepts of WebSockets in a simple yet functional way.

#project structure* chat-app/ |---node module ├── server.js ├── public/ │ ├── index.html │ ├── style.css │ └── script.js ├── package.json └── package-lock.json
