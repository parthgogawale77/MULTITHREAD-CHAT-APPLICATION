# MULTITHREAD-CHAT-APPLICATION

COMPONY: CODETECH IT SOLUTIONS

NAME: PARTH NAMDEV GOGAWALE

INTERN ID: CTIS9713

DOMAIN: JAVA PROGRAMMING

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

DESCRIPTION:
The Multithreaded Chat Application is a client-server based communication system developed using Java Socket Programming and Multithreading concepts. The primary objective of this project is to enable multiple users to communicate with each other in real time through a centralized server. This application demonstrates the practical implementation of networking concepts, concurrent programming, and client-server architecture in Java.
In this project, a server application is created that listens for incoming client connections on a specific port. Whenever a new client connects, the server accepts the connection and creates a separate thread dedicated to handling communication with that client. This multithreading approach ensures that multiple clients can connect and communicate simultaneously without affecting the performance of other connected users.
The client application allows users to connect to the server by specifying the server's IP address and port number. Once connected, users can send and receive messages in real time. Messages entered by one client are transmitted to the server, which then broadcasts them to all other connected clients. This creates a group chat environment where multiple participants can communicate seamlessly.
The application utilizes Java's Socket and ServerSocket classes to establish network communication. The ServerSocket class is responsible for listening to incoming connection requests, while the Socket class facilitates data exchange between the server and clients. Input and output streams are used to send and receive messages over the network efficiently.
Multithreading plays a crucial role in the application's functionality. Each client connection is managed by an independent thread, allowing the server to handle multiple users concurrently. Without multithreading, the server would only be able to communicate with one client at a time, significantly limiting its usability. By assigning a dedicated thread to each client, the application ensures smooth and responsive communication even when several users are connected simultaneously.
The project also includes basic error handling mechanisms to manage client disconnections and network-related issues. When a client leaves the chat, the server detects the disconnection and removes the client from the active user list. This prevents communication errors and helps maintain the stability of the application.
One of the major advantages of this project is its scalability. Additional features such as private messaging, user authentication, message encryption, chat rooms, and graphical user interfaces can be integrated in future versions. These enhancements would make the application more secure, user-friendly, and suitable for real-world communication systems.
The Multithreaded Chat Application provides valuable experience in Java networking and concurrent programming. It helps developers understand how modern communication platforms manage multiple users and real-time data exchange. Through the implementation of sockets, threads, and client-server architecture, this project demonstrates the core principles behind network-based applications and distributed systems.
In conclusion, the Multithreaded Chat Application successfully achieves real-time communication among multiple users using Java Sockets and Multithreading. It serves as an excellent educational project for understanding networking fundamentals, thread management, and the development of scalable client-server applications. The project highlights the effectiveness of Java in building reliable and efficient communication systems.

OUTPUT : 
<img width="1470" height="956" alt="Image" src="https://github.com/user-attachments/assets/17f6541f-1e58-43f5-963d-c00c4662cd76" />
