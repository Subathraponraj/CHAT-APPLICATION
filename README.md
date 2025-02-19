# CHAT-APPLICATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: PAVITHRA P

*INTERN ID*: CT08TFT

*DOMAIN*: FULL STACK WEB DEVELOPMENT

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH

*DESCRIPTION*:I have developed a real time chat application that delivers smooth and efficient messaging, allowing users to send and receive messages instantly while incorporating features that enhance usability and engagement.Whether for casual conversations or quick exchanges, this chat application provides a seamless experience with a clean and structured interface that make communication both effective and enjoyable.This real-time chat application is built using a simple tech stack consisting of HTML, CSS, and JavaScript for the frontend and Node.js with Socket.io for the backend. The application has a visually distinct chat interface that differentiates sent and received messages.

The frontend of the chat application is structured using HTML and styled with CSS to create a clean and user-friendly interface. Users can type messages in a text box with a placeholder labeled "Text message" and send them using a button. Another button allows users to input messages using voice recognition. Messages appear on the left for one user and on the right for another, with sent messages displayed in medium purple and received messages in white. This design enhances readability and improves user experience.

The JavaScript file on the client side manages user interactions and real-time communication with the server using Socket.io. When a user sends a message, the text is processed to convert common emoji characters like ":)", ":(", ":D", and ":P" into their corresponding emoji symbols. The message is then emitted to the server using a WebSocket connection. The script also listens for incoming messages from other users and appropriately aligns them to the left or right based on the sender's unique user ID.

The backend is developed using Node.js and Express.js, with Socket.io handling real-time communication between users. Upon connection, each user is assigned a WebSocket session, and messages sent by one user are broadcasted to all connected clients. The server listens for messages and ensures that they are transmitted to all participants instantly. When a user disconnects, a console log message is generated to indicate the event.

One of the application's unique features is its voice input functionality, implemented using the Web Speech API. When a user clicks the voice button, the browser's speech recognition feature is activated, allowing users to speak instead of typing. The recognized speech is converted into text and displayed in the input box. This functionality makes the chat accessible to users who prefer voice input over typing.Another key feature is the integration of emoji conversion, which enhances the expressiveness of messages. When users type certain text-based emoticons, they are automatically replaced with their graphical emoji equivalents, making conversations more engaging.

The application does not use a database or file-based storage, as it is designed for real-time ephemeral communication. All messages exist only in the session and are lost upon refresh or disconnection. The lack of persistent storage simplifies deployment and ensures a lightweight architecture.Overall, this chat application provides a lightweight and efficient solution for real-time communication, leveraging for instant messaging and modern web technologies for an interactive user experience. The combination of Node.js, Express.js, and Socket.io ensures seamless performance, while HTML, CSS, and JavaScript enhance usability and aesthetics. Features like voice input, emoji conversion, and structured message alignment make the application both functional and user-friendly.

*OUTPUT*:
![Image](https://github.com/user-attachments/assets/af07e0ec-7720-4b77-86f8-9c74116c6240)

![Image](https://github.com/user-attachments/assets/d433049f-7630-40a2-9a55-340da2f5763a)

![Image](https://github.com/user-attachments/assets/4f1edffe-32ed-43d0-9f6b-d7620efaaf0b)

![Image](https://github.com/user-attachments/assets/98296565-a2ac-4d08-9278-6841f316d66c)

![Image](https://github.com/user-attachments/assets/210080f4-b575-4815-a60f-432a84b11dac)





