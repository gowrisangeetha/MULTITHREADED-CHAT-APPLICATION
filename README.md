COMPANY: CODTECH IT SOLUTIONS

NAME: GOWRI SANGEETHA V 

INTERN ID: CT08VKR

DOMAIN: JAVA PROGRAMMING 

DURATION: 4 WEEEKS

MENTOR: NEELA SANTOSH

Overview

This is a multithreaded client-server chat application built using Java Sockets. The server handles multiple clients concurrently, allowing real-time communication between users.

Features

Supports multiple clients connecting to the server.

Clients can send and receive messages in real-time.

Server broadcasts messages to all connected clients.

Uses multithreading to handle concurrent client connections.

Requirements

Java 8 or later

VS Code (or any Java-supported IDE)

Java Extension Pack (for VS Code)

A terminal to run the server and multiple clients

Setup & Installation

1. Clone or Download the Repository

git clone https://github.com/your-repo/chat-app.git
cd chat-app

Or manually create a folder and add ChatServer.java and ChatClient.java.

2. Compile the Java Files

Open a terminal in VS Code and run:

javac ChatServer.java ChatClient.java

3. Run the Server

java ChatServer

You should see:

Chat Server started on port 12345

4. Run Clients (Multiple Instances)

Open a new terminal for each client and run:

java ChatClient

Each client will be prompted to enter their name and start chatting.

How It Works

The server listens for incoming client connections.

Each client connects, enters their name, and starts sending messages.

The server broadcasts each message to all connected clients.

When a client disconnects, the server notifies other clients.



---

Example Output

Server Output

Chat Server started on port 12345
Alice has joined the chat.
Bob has joined the chat.
Alice: Hello, everyone!
Bob: Hi Alice!

Client 1 (Alice)

Enter your name:
Alice
Bob has joined the chat.
Bob: Hi Alice!

Client 2 (Bob)

Enter your name:
Bob
Alice: Hello, everyone!

Customization

Change the server port in ChatServer.java (default: 12345).

Modify SERVER_IP in ChatClient.java if running on a different network.

OUTPUT

