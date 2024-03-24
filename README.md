# Rust Chat App

This is a simple chat application built using Rust, Actix WebSocket, HTML, and CSS. The application supports both private chat and group chat functionalities.

## Features

- Private Chat: Users can send private messages to specific recipients by mentioning their recipient's ID in the message.
- Group Chat: Users can send messages to everyone in the chat room.
- Real-time Communication: The application uses WebSocket for real-time communication between the server and clients.

## Instructions

1. **Clone the Repository**: Clone this repository to your local machine.

    ```bash
    git clone https://github.com/divyarang24/Rust_chat_app.git
    ```

2. **Navigate to the Project Directory**: Move into the project directory.

    ```bash
    cd Rust_chat_app
    ```

3. **Build and Run the Server**: Build and run the Rust server.

    ```bash
    cargo run
    ```

4. **Access the Application**: Open your web browser and go to `http://localhost:3001`.

5. **Connect to the Server**: Click the "Connect" button to connect to the server. You may need to open another tab and repeat this step if you want to connect with multiple clients.

6. **Start Chatting**:
   - **Private Chat**: To send a private message, use the format `@message recipient_id`, for example, `@hi 1114546579`.this recipient_id you will get in the terminal,
   - **Group Chat**: Simply type your message and press enter to send it to everyone in the chat room.

## Notes

- Due to time constraints, not all features may be fully implemented. This project serves as a basic demonstration of a chat application using Rust.

Enjoy chatting! 🚀
