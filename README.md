# springboot-chatapp
# Chat Application Project
This is a chat application project that allows users to communicate with each other in real-time. It is built using the Spring Boot framework for the backend, SockJS for WebSocket communication, and React for the frontend. The project utilizes Maven as the build tool for the backend.

# Features
User Authentication: Users are required to log in with a username before they can access the chat application.
Real-time Chat: Once logged in, users are directed to the chat page where they can send messages in the chatroom.
User Presence: Users are notified when new users join the chatroom, allowing them to be aware of other participants.
Private Messages: Users have the ability to send private messages to specific individuals.
Multimedia Transfer: The application supports the transfer of multimedia files, such as photos and videos.
Logout: Users can log out from the application, and their username will be removed from the user list displayed to other participants.
Tech Stack
The application incorporates the following technologies:

Spring Boot: A Java-based framework used for building the backend server and handling business logic.
SockJS: A WebSocket emulation library that enables real-time communication between the server and clients.
React: A JavaScript library used for building the user interface and handling frontend functionality.
Setup Instructions
To run the chat application locally, follow these steps:


Navigate to the project directory: cd chatroom-backend
Set up the backend server:
Install the necessary dependencies: mvn clean install
Start the Spring Boot server: mvn spring-boot:run
Set up the frontend:
Install the necessary dependencies: cd chatroom-ui && npm install
Start the React development server: npm run dev
Open your web browser and visit http://localhost:5173 to access the chat application
