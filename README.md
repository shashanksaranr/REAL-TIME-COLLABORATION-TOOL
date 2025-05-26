# REAL-TIME COLLABORATION TOOL

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SHASHANKSARAN R

*INTERN ID*: CT4MVTZ

*DOMAIN*: SOFTWARE DEVELOPMENT

*DURATION*: 4 MONTHS (16 WEEKS)

*MENTOR*: NEELA SANTOSH

# Description:

As part of my software development internship at CodTech, I designed and developed a Real-Time Collaboration Tool using WebSocket, Node.js, and React. The tool enables multiple users to collaborate on shared documents, projects, or workspaces in real-time, making it an ideal solution for teams and remote collaborations. The main objective was to create an interactive and responsive platform that allows users to make changes simultaneously, see each other’s updates instantly, and work together without delays, improving productivity and communication.

This collaboration tool features real-time synchronization, user authentication, file sharing, and live chat functionalities. The application was built to provide a seamless user experience, allowing users to join a shared workspace, make edits, send messages, and upload files without refreshing the page. It ensures that all connected users see updates and changes instantly, making it perfect for use in educational environments, remote work, and creative collaboration.

# Tools and Technologies Used:

1. WebSocket
WebSocket was used for real-time communication between the client and the server. It allows for a persistent connection, which ensures that any changes made by a user (text edits, file uploads, etc.) are instantly transmitted to other users without needing to refresh the page. This makes collaboration seamless and synchronized across all users in real time.

2. Node.js
Node.js served as the backend of the application, enabling server-side JavaScript to handle WebSocket connections and manage real-time communication. I used Express.js as the server framework to handle routing, requests, and WebSocket connections. The server was built to manage authentication, broadcast changes to connected users, and provide an efficient way to store and retrieve data in real-time.

3. React
React was used to build the frontend of the collaboration tool. With React, I created a dynamic, component-based user interface that allows users to interact with the application in real-time. React’s state management was used to reflect changes in the document or workspace instantly without the need for page reloads. Components like workspaces, message panels, and file upload sections were implemented using React to maintain a smooth and responsive UI.

4. MongoDB
MongoDB was used to store user authentication information and session data. It provided a flexible schema to store documents and user settings, ensuring scalability as the application grows and new features are added.

# Key Features Implemented:

1. Real-Time Collaboration: Users can edit documents or workspaces simultaneously, and changes are broadcasted instantly to all other connected users.

2. User Authentication: Secure login system with JWT (JSON Web Tokens) for user authentication and session management. Only authorized users can access specific workspaces.

3. Shared Workspace: Multiple users can work in the same workspace, with all changes visible to others in real time. It supports features like text editing, file sharing, and live chat.

4. Live Chat: A messaging system where users can communicate instantly, providing a channel for discussions, comments, and feedback during the collaborative process.

# Design Philosophy:

The design of the Real-Time Collaboration Tool follows modern web development principles, prioritizing usability, accessibility, and seamless real-time interactions. I adopted a minimalist approach to the user interface, focusing on clarity and ease of navigation. The layout was designed to encourage user collaboration, with clear sections for document editing, messaging, and file sharing.

Responsive design was essential, ensuring that the tool works well on different devices, including desktops, tablets, and mobile phones. I used CSS Flexbox and Grid systems to create a responsive layout that adjusts according to the screen size, ensuring the tool remains functional and aesthetically appealing across various devices.

By leveraging React’s component-based architecture, I ensured that updates made by users are efficiently reflected on their screens, minimizing load times and enhancing user experience. Overall, the tool was designed with the intent to create an intuitive and reliable platform for collaborative work, removing the barriers that slow down progress in remote teams and group projects.

# Installation

Prerequisites: Make sure you have Node.js and npm installed.

# Steps to Run the Application

1. Clone the repository:

    git clone https://github.com/shashanksaranr/real-time-collaboration-tool.git

2. Navigate to the project directory:

    cd real-time-collaboration-tool

3. Install the backend dependencies:

    cd server
   
    npm install
   
4. Run the backend server:

    In the terminal, run:
   
      node server.js

5. Create React App called Client:

   In terminal:
   
           create-react-app client
   
    Open a new terminal window for the frontend and navigate to the client folder:

       cd ../client
   
7. Install the frontend dependencies:

       npm install
  
9. Start the frontend development server:

       npm start
  
  The app will be available at http://localhost:5005.


# Output:

1. Real Time Collaboration Tool Window

   <img width="1728" alt="Image" src="https://github.com/user-attachments/assets/4835cbd6-7503-4ff3-8aed-60355d1a6342" />

2. User 1 Typing Message (On Left Side)

   <img width="1728" alt="Image" src="https://github.com/user-attachments/assets/f7d64740-82b4-46c9-9ddb-428ffa161d5b" />

3. User 2 Typing Message (On Right Side)

   <img width="1728" alt="Image" src="https://github.com/user-attachments/assets/ad3e9aa0-1849-4891-acaa-9da6fb422efe" />


🙋‍♂️ Author

SHASHANKSARAN R

GitHub: @shashanksaranr   



  
