🖬 Chat Application - Real-Time Messaging with WebSockets 🚀

📚 Overview

This is a real-time chat application built using Spring Boot (Java) for the backend and HTML, JavaScript, and WebSockets (STOMP & SockJS) for the frontend. The app allows multiple users to send and receive messages instantly.

🌟 Features

✅ Real-time messaging using WebSockets (STOMP & SockJS)✅ Multi-user support with instant message updates✅ User-friendly interface with Bootstrap✅ Simple and scalable WebSocket configuration

⚙️ Tech Stack

Backend: Java, Spring Boot, WebSockets (STOMP)

Frontend: HTML, JavaScript, Bootstrap

Libraries: SockJS, STOMP.js

📚 Project Structure

/chat-app
 ├── src/main/java/com/chat/app
 │   ├── ChatApplication.java            # Main Spring Boot Application
 │   ├── config/WebSocketConfig.java     # WebSocket Configuration
 │   ├── controller/ChatController.java  # Handles chat messages
 │   ├── model/ChatMessage.java          # Chat message model
 │
 ├── src/main/resources/templates
 │   ├── chat.html                       # Frontend UI (HTML + JS)
 │
 ├── pom.xml                              # Maven dependencies
 ├── README.md                            # Project documentation

🚀 How to Run

1️⃣ Clone the Repository

git clone https://github.com/your-username/chat-app.git
cd chat-app

2️⃣ Run the Spring Boot Server

mvn spring-boot:run

3️⃣ Open Browser and Access the Chat App

http://localhost:8080/chat

4️⃣ Start Chatting!

Open multiple browser tabs and send messages in real time. 🎉

🛠️ Dependencies

Add these dependencies to pom.xml:

<dependencies>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-web</artifactId>
    </dependency>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-websocket</artifactId>
    </dependency>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-messaging</artifactId>
    </dependency>
    <dependency>
        <groupId>org.projectlombok</groupId>
        <artifactId>lombok</artifactId>
        <scope>provided</scope>
    </dependency>
</dependencies>

🖼️ Screenshots

🖼️ Coming soon! (Add screenshots of your chat interface here)

🛠️ Future Enhancements

🔹 User authentication (Spring Security + JWT)🔹 Chat rooms and group messaging🔹 Message persistence with a database (MySQL, PostgreSQL)

📝 License

This project is open-source. Feel free to contribute!

Let me know if you want any modifications! 🚀

