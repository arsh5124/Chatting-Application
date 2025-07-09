# Chatting-Application

This Java-based chatting application enables real-time messaging between multiple clients connected to a central server. Using socket programming, it supports reliable TCP/IP communication for stable data transfer, with a potential for UDP support in future versions.

## Key Features
- **Client-Server Architecture**: The server manages multiple client connections, facilitating smooth message exchanges.
- **User-Friendly Interface**: Built with Java Swing and AWT, providing a simple, intuitive graphical user interface.
- **Reliable Communication**: Utilizes TCP protocol for secure, ordered data delivery across clients.
  
## How It Works
The server listens for incoming client connections on a specific port, creating a dedicated link for each client. Once connected, clients can communicate with one another via the server, allowing seamless interaction in real time.
