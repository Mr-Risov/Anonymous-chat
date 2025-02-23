# Anonymous Chat

Anonymous Chat is a simple real-time web-based chat application that allows users to communicate anonymously. This project utilizes PieSocket for WebSocket-based communication.

## Features
- Real-time chat functionality
- Unique username generation for each user
- Message persistence using cookies
- User join notifications
- Simple and clean UI design

## How It Works
1. When a user opens the chat page, they are assigned a random username (e.g., `user_123`).
2. The application connects to PieSocket, a WebSocket service, to establish a real-time communication channel.
3. When a user joins, a system message notifies all participants.
4. Users can send messages by typing into the input field and clicking the send button.
5. Messages are broadcasted to all users in the chat room using WebSockets.
6. Messages are stored in cookies to retain chat history for the user.
7. The chat interface updates dynamically as new messages arrive.

## Technologies Used
- HTML, CSS, JavaScript
- PieSocket WebSockets

## Setup Instructions
1. Open `https://Mr-Risov.github.io/Anonymous-chat/` in a browser.
- Type a message and click send to participate in the chat.
- Your messages will be stored using cookies for later retrieval.

## License
This project is open-source and available under the MIT License.

## Author
[Mr-Risov] - [GitHub Profile](https://github.com/Mr-Risov/)


