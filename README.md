# UDP Chatroom

**Overview:**

Implement a simple yet powerful chatroom using Python sockets. This project comprises both client and server scripts that enable users to engage in real-time conversations over a local network. The chatroom employs the UDP protocol for efficient communication, making it an ideal choice for lightweight and responsive chat applications.

**Features:**

- **Dynamic Port Assignment:** The client script randomly assigns a port between 8000 and 9000 for each user, ensuring a secure and scalable solution.

- **Threaded Communication:** Utilizes threading to manage concurrent tasks, allowing users to send and receive messages simultaneously without interruptions.

- **User Registration:** Clients can register their nicknames using the "SIGNUP_TAG" feature, providing a personalized touch to the chatroom experience.

## Client

The client script establishes a UDP connection, binds to a dynamically assigned port, and allows users to send and receive messages. The user-friendly interface prompts for a nickname and supports the "!q" command to exit the chatroom.

## Server

The server script listens on a predefined port for incoming messages, managing a queue to handle concurrent message reception. It broadcasts messages to all connected clients, ensuring that everyone stays in sync. Additionally, it handles user registration messages, welcoming new users to the chatroom.

## Usage

1.Clone the repository:

   ```bash
   git@github.com:Arash97-Projects/Socket.git
   ```

2.Run the server script:

  ```bash
  python server.py
  ```

3.Run the client script for each user:

  ```bash
  python client.py
  ```

4.Follow the on-screen instructions to set nicknames, send messages, and enjoy seamless communication.

**Contribution:**

Feel free to contribute, report issues, or suggest enhancements. Your contributions are highly valued in making this chatroom project even more robust and user-friendly.







# TCP Chatroom

Welcome to the TCP Chat Room project, where we undertake the development of a straightforward yet robust communication system. This initiative brings forth a server-client architecture, enabling multiple users to connect and communicate seamlessly within a real-time chat environment. The primary objective of this project is to furnish an interactive platform, allowing users to establish connections with a central server and participate in dynamic conversations.


## Project Overview:

**Our TCP chat room consists of two main components:**

  - **Server:** The heart of the chat room, the server facilitates connections from multiple clients. It manages the communication between clients, ensuring a smooth and efficient exchange of messages. The server is responsible for handling new connections, assigning unique nicknames to clients, and broadcasting messages to all connected users.

  - **Clients:** These are the end-users who connect to the server to participate in the chat. Clients can choose a nickname for identification purposes and engage in real-time conversations with other connected users. The system is designed to handle multiple clients concurrently, allowing for a dynamic and interactive chat experience.

**Key Features**

   - **Real-Time Communication:** Experience instant messaging with real-time updates, creating a lively and engaging chat environment.

   - **Nickname Assignment:**  Clients can personalize their chat experience by choosing unique nicknames for easy identification during conversations.

   - **Error Handling:** The system gracefully handles errors and disconnections, ensuring a robust and reliable chat room experience.



## License

This project is licensed under the MIT License.
