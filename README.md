# Real-Time Chat Apps using Spring, Cassandra, Redis, WebSocket and RabbitMQ

![Chat Application](/images/ebook-chat-application.png)

# Technologies used in this project

- Spring Boot
- Spring Data (JPA / Cassandra / Redis)
- Spring Security
- Spring WebSocket
- Spring Session
- Cassandra
- Redis
- RabbitMQ
- MySQL
- JUnit, Mockito and TestContainers (spin up Docker containers for Integration Tests)
- Thymeleaf, JQuery and Bootstrap
- Apache Maven (Surefire and Failsafe plugins)

# Setting up this project locally

> **Note:**
The fastest way to get this application up and running locally is using **Docker** and **Docker Compose**.  Be sure that you have at least **Docker 1.13.0** and **Docker Compose 1.11.2** installed on your machine.

1. Clone this repository:
```shell
$ git clone https://github.com/qnfm/Spring-Boot-Full-Stack-Chat-App.git
```

2. Enter the repository directory:
```shell
$ cd Spring-Boot-Full-Stack-Chat-App
```

3. Set up the dependencies (Cassandra, Redis, MySQL and RabbitMQ with STOMP support):
```shell
$ docker-compose -f docker-compose/dependencies.yml up
```

4. Download and start the application:
```shell
$ wget https://github.com/qnfm/Spring-Boot-Full-Stack-Chat-App/releases/download/chat-1.0.0/chat-1.0.0.jar && java -jar chat-1.0.0.jar
```

5. Navigate to `http://localhost:8080` and have fun!

# Basic Usage

1. Sign in with username **admin** and password **admin**
2. Create a **New Chat Room** and logout
3. Create your private account
4. Sign in with your account credentials
5. Join the chat room
6. Open a new incognito window and create another account
7. Sign in with this another account
8. Join the chat room
9. Send some messages
10. Open the other browser window and see the messages coming
11. Click the username to send private messages
