# Python Socket Chatroom

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

1. Clone the repository:

   ```bash
   git@github.com:Arash97-Projects/Socket.git
```

2. Run the server script:

  ```bash
  python server.py
```

3. Run the client script for each user:

  ```bash
  python client.py
```

4. Follow the on-screen instructions to set nicknames, send messages, and enjoy seamless communication.

**Contribution:**

Feel free to contribute, report issues, or suggest enhancements. Your contributions are highly valued in making this chatroom project even more robust and user-friendly.
