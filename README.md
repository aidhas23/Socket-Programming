# Socket Programming Projects

Welcome to my repository showcasing projects related to **Socket Programming**! In this collection, you'll find two main projects that demonstrate how to work with sockets for various networking tasks.

## 📚 Overview

This repository includes examples of network communication through socket programming, where I explore both basic and advanced networking concepts:

- **Packet Sniffer**: Using Python to capture and analyze network packets.
- **Client-Server Chat Application**: Using C to create a basic chat application that communicates over a network using sockets.

## 💻 Projects

### 1. **Simple Packet Sniffer Using Sockets in Python**
   - Developed a **packet sniffer** using Python and the `socket` library to capture and analyze network packets.
   - The program listens on a specific interface, intercepting incoming and outgoing packets.
   - Analyzed packet data to extract useful information like source/destination IP, port numbers, and protocol.
   - This project helps in understanding how packet-level communication works and how data is transmitted across networks.
   
   #### Key Features:
   - Captures packets on a given network interface.
   - Displays basic information (source IP, destination IP, ports, etc.).
   - Written in Python using the `socket` and `struct` libraries.

   #### Getting Started:
   1. Clone the repository:
      ```bash
      git clone https://github.com/aidhas23/socket-programming-projects.git
      ```
   2. Navigate to the project folder and run the script:
      ```bash
      cd simple-packet-sniffer
      python packet_sniffer.py
      ```

### 2. **Chat Program: Client-Server Relationship Using Sockets in C**
   - Developed a **chat program** using C that implements a client-server relationship through TCP sockets.
   - The client connects to a server, sends messages, and receives responses.
   - The server listens for incoming client connections, handles multiple clients, and facilitates message exchange.
   - This project demonstrates the core concepts of socket-based communication, handling incoming connections, and maintaining persistent connections for real-time communication.

   #### Key Features:
   - TCP-based communication between client and server.
   - Simple user interface for sending and receiving messages.
   - Supports real-time, bidirectional messaging.
   - Written in C using the `socket` and `stdio` libraries.

   #### Getting Started:
   1. Clone the repository:
      ```bash
      git clone https://github.com/aidhas23/socket-programming.git
      ```
   2. Navigate to the project folder and compile the code:
      ```bash
      cd Chat Programm Client Server
      gcc server.c -o server
      gcc client.c -o client
      ```
   3. Run the server in one terminal window:
      ```bash
      ./server
      ```
   4. Run the client in another terminal window:
      ```bash
      ./client
      ```

## 🔧 Tools and Technologies

- **Python**: For the packet sniffer project using Python's `socket` library.
- **C**: For the chat program using C's `socket` library.
- **Wireshark**: Optionally used to analyze the network traffic captured by the packet sniffer.
- **Linux**: Recommended OS for running these projects, especially the packet sniffer (requires root permissions).

