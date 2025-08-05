# 💬 Real-Time Chat Application

A real-time chat application built using **Spring Boot**, **WebSocket (STOMP over SockJS)**, **Thymeleaf**, and **JavaScript**. This project demonstrates bi-directional communication between client and server using WebSockets in a lightweight full-stack application.

---

## 🚀 Features

- Real-time message broadcasting using WebSocket and STOMP protocol
- Spring Boot backend with message broker and STOMP endpoint configuration
- Dynamic frontend with Thymeleaf, JavaScript, and Bootstrap
- STOMP over SockJS for seamless communication across clients
- Auto-scroll message window for a clean chat experience

---

## 🛠️ Tech Stack

- **Java 17+**
- **Spring Boot**
- **Spring WebSocket / STOMP**
- **Thymeleaf**
- **SockJS + STOMP.js**
- **Bootstrap 5**

---


## 📁 Project Structure

src/
├── main/
│ ├── java/com/chat/app/
│ │ ├── config/ # WebSocketConfig.java
│ │ ├── controller/ # ChatController.java
│ │ ├── model/ # ChatMessage.java
│ │ └── AppApplication.java # Main Spring Boot class
│ └── resources/
│ ├── templates/ # chat.html (Thymeleaf view)
│ └── application.properties



## 💻 Run Locally

### Prerequisites:
- Java 17+
- Maven

### Steps:

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/springboot-realtime-chat.git
cd springboot-realtime-chat

# Run the application
./mvnw spring-boot:run
Access the chat app:
bash
Copy
Edit
http://localhost:8080/chat



📌 Usage
Enter your name in the "Your name..." field.

Type a message and click "Send".

Watch messages broadcast live across all open tabs/sessions.

## 📁 Project Structure

