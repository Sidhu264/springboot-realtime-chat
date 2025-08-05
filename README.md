# 💬 Real-Time Chat Application

A real-time chat application built using **Spring Boot**, **WebSocket (STOMP over SockJS)**, **Thymeleaf**, and **JavaScript**. This project demonstrates bi-directional communication between client and server using WebSockets in a lightweight full-stack setup.

---

## 🚀 Features

- Real-time message broadcasting using WebSocket and STOMP
- Spring Boot backend with message broker and STOMP endpoint
- Dynamic frontend using Thymeleaf and JavaScript
- STOMP over SockJS for reliable client communication
- Auto-scrolling chat window for clean UX

---

## 🛠️ Tech Stack

- Java 17+
- Spring Boot
- Spring WebSocket / STOMP
- Thymeleaf
- SockJS + STOMP.js
- Bootstrap 5

---


## 💻 Run Locally

### Prerequisites

- Java 17+
- Maven

### Steps

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/springboot-realtime-chat.git
cd springboot-realtime-chat

# Run the application
./mvnw spring-boot:run
```

### Open in your browser
http://localhost:8080/chat


### How to Use
1. Enter your name in the input field.
2. Type a message and click Send.
3. Messages will appear live across all open browser sessions in real time.




