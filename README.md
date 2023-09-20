# VueChat
VueJs multi-user chat app
Real-Time Chat Application with Agora RTM and Vue.js

This is a real-time chat application built using Agora Real-Time Messaging (RTM) and Vue.js. It allows users to join a chat channel, send messages, and receive messages in real-time. The application uses Agora RTM for the real-time messaging functionality and Vue.js for the user interface.

# Features
Real-time messaging: Users can send and receive messages in real-time.
Simple and intuitive UI: The user interface is designed to be user-friendly and responsive.
Message history: Chat messages are displayed in a scrollable chat panel.
User identification: Messages are tagged with "You" or "Them" to distinguish between user and peer messages.

# Prerequisites

Before running this application, you need to have the following:

Agora App ID: You can obtain this by creating an account on the Agora website.
Node.js and npm: Make sure you have Node.js and npm installed on your system.
Getting Started
Clone the repository to your local machine:

git clone https://github.com/yourusername/real-time-chat-app.git
Change directory to the project folder:

cd real-time-chat-app
Install the project dependencies:

npm install
Configure your Agora App ID:

Open the App.vue file and replace the APP_ID constant with your Agora App ID:


const APP_ID = 'your-agora-app-id';
Run the application:

npm run serve
Open your web browser and navigate to http://localhost:8080 to use the chat application.

# Usage
Type your message in the text input field and press the "+" button or hit Enter to send the message.
Messages sent by you will be tagged as "You," while messages from other users will be tagged as "Them."
Scroll through the chat panel to view message history.
Enjoy real-time chat with other users!

# Built With
Agora RTM SDK
Vue.js
uuid

# Acknowledgments
Special thanks to the Agora team for providing the Agora RTM SDK.
Inspiration: Web Dev Cody
