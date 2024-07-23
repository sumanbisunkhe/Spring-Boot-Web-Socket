# Chat Room Application

Welcome to the Chat Room Application! This project is a real-time chat application built with Spring Boot and WebSocket technology using STOMP protocol. It provides a dynamic interface for users to connect, send messages, and receive real-time updates.

## Features

- **Real-Time Messaging**: Communicate instantly using WebSocket with STOMP protocol.
- **User-Friendly Interface**: Simple and intuitive UI for chatting.
- **Server-Side Handling**: Efficient message handling and broadcasting by the Spring Boot server.

## Project Structure

- **`src/main/java/org/example/chatroom/config/WebSocketConfig.java`**: Configures WebSocket and STOMP endpoints.
- **`src/main/java/org/example/chatroom/controller/MessageController.java`**: Manages message receipt and broadcasting.
- **`src/main/java/org/example/chatroom/model/Message.java`**: Defines the structure of chat messages.
- **`src/main/java/org/example/chatroom/model/OutputMessage.java`**: Defines the format of messages sent to clients.
- **`src/main/resources/static/index.html`**: The primary HTML file for the chat user interface.
- **`src/main/resources/static/js/sockjs-0.3.4.js`**: SockJS library for WebSocket support.
- **`src/main/resources/static/js/stomp.js`**: STOMP client library for WebSocket messaging.
- **`src/main/resources/application.properties`**: Configuration settings for the Spring Boot application.

## Getting Started

### Prerequisites

- **Java 17** or higher
- **Maven** for building the project
- A modern web browser

### Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/sumanbisunkhe/Web-Socket.git
    cd Web-Socket
    ```

2. **Build the Project**:
    ```bash
    mvn clean install
    ```

3. **Run the Application**:
    ```bash
    mvn spring-boot:run
    ```

4. **Access the Chat Interface**:
    Open your web browser and navigate to [http://localhost:8080/index.html](http://localhost:8080/index.html).

## Usage

1. **Connecting to the Chat**:
    - Enter a nickname in the input field and click the "Connect" button.

2. **Sending Messages**:
    - Type your message in the provided input field and click the "Send" button to broadcast it.

3. **Disconnecting**:
    - Click the "Disconnect" button to end your chat session.

## Troubleshooting

- **WebSocket Connection Issues**:
  - Check the browser console for errors related to WebSocket connections.
  - Ensure the WebSocket server is running and accessible.

- **Message Sending/Receiving Issues**:
  - Verify that the WebSocket connection is properly established.
  - Check server logs for any errors in message handling.

## Contributing

Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request. Your feedback and improvements are highly valued.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For questions or support, please reach out to [sumanbisunkhe304@gmail.com](mailto:sumanbisunkhe304@gmail.com).

---

Thank you for using the Demo Chat Room Application. Enjoy chatting!
