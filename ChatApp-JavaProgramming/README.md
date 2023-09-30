# Java Socket Programming - Distributed System Demo

This project demonstrates basic Java Socket Programming and illustrates how it can be related to distributed systems. It includes two main tasks:

- [Creating Multiple Clients with Thread Pool](#creating-multiple-clients-with-thread-pool)
- [Configuring the Server for Peer-to-Peer Communication](#configuring-the-server-for-peer-to-peer-communication)

## Creating Multiple Clients with Thread Pool

In a distributed system, multiple clients often need to interact with a central server simultaneously. To simulate this scenario, we create a server that can handle multiple client connections concurrently using a thread pool. This allows clients to connect and interact with the server independently.

- Server: `Server.java`
- Client: `Client.java`

To run the server and multiple clients, follow the instructions in the respective Java files. This task demonstrates how a server can efficiently manage and communicate with multiple clients in a distributed system.

## Configuring the Server for Peer-to-Peer Communication

In a distributed system, clients not only interact with the server but can also communicate with each other. In this task, we extend the server's functionality to facilitate direct communication between clients.

- Server: `Server.java`
- Client: `Client.java`

Clients can send messages to the server, and the server acts as a message broker, forwarding messages from one client to another. This task showcases how a central server can be used to enable peer-to-peer communication among clients in a distributed system.

## Running the Project

To run this project, you will need Java installed on your system. Follow these steps:

1. Compile the Java files

2. Start the server:

3. Start multiple clients (in separate terminals)

You can run multiple client instances to simulate concurrent interactions.

4. Follow the prompts in the clients to send and receive messages.

## About Distributed Systems

Distributed systems involve a collection of interconnected computers that work together to achieve a common goal. In this project, the server represents a central component that manages client connections and communication. This demonstrates how distributed systems can use socket programming to enable communication and collaboration among multiple entities.

Happy coding!


