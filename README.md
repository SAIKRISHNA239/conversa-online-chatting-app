
<div align="left" style="position: relative;">
  
<div style="display: flex; justify-content: space-between; align-items: center; width: 100%;">
  <div>
    <h1>Conversa - MERN Chatting Application</h1>
    <em>Connect, Code, Converse - Anywhere, Anytime with MERN Chat App!</em>
    <p>A full-stack MERN (MongoDB, Express.js, React.js, Node.js, Socket.IO) online chatting application 💬 with friends additionally with a Personal Chatbot. 🤖</p>
  </div>
</div>
## 🚀 Getting Started

### ☑️ Prerequisites

- **Version Controller** Git
- **Programming Language:** JavaScript/Node.js
- **Package Manager:** Npm

### ⚙️ Installation

Install mern-chat-app using one of the following methods:

**Build from source:**

1. Navigate to the project directory:
	```
	cd mern-chat-app
	```

2. Setup Backend
	- Install Dependencies
	    ```
	    cd backend
	    npm install
	    ```
   - Setup Environment: Create a **.env** file in the backend folder and add necessary environment variables.
	    ```
	    PORT=5000
	    GENERATIVE_API_KEY = ""
	    MONGO_URI = ""
	    EMAIL = ""
	    PASSWORD= ""
	    CLOUDINARY_ClOUD_NAME = ""
	    CLOUDINARY_API_KEY = ""
	    CLOUDINARY_API_SECRET = ""
	    JWT_SECRET = ""
	    AWS_ACCESS_KEY = ""
	    AWS_SECRET = ""
	    AWS_BUCKET_NAME = ""
	    ```
    
3. Setup Frontend
	- Install Dependencies
	    ```
	    cd frontend
	    npm install
	    ```

### 🤖 Usage

1. Start the backend server:
    ```
    cd backend
    nodemon ./index.js
    ```
2. Start the frontend development server:
    ```
    cd frontend
    npm run start
    ```
---	
### Conversa is a chat-app with various features like:
-   🔐 **Authentication**:  
    ✨ SignUp,  
    🔑 Login,  
    📲 Login with OTP,  
    📸 Profile Photo Uploading.
    
-   🎨 **Styling/Theming**:  
    🌐 A fully responsive app,  
    🌙 Dark and ☀️ Light mode.
    
-   🤖 **Personalized AI Chatbot**:  
    🧠 Remembers the context for personalized interactions.
    
-   🌐 **Web Sockets**:  
    💬 Real-time chatting,  
    🔔 Message Notifications,  
    🖋️ Real-Time Typing Animation,  
    ❌ Message Deletion,  
    🟢 Active Now / ⌛ Last Seen status tracking,  
    ✅ Message Seen status,  
    🖼️ Sending Image messages with captions.

</p>

<p align="left">Built with the tools and technologies:</p>
<p align="left">
	
![npm](https://img.shields.io/badge/npm-CB3837.svg?style=flat&logo=npm&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%2347A248.svg?style=flat&logo=mongodb&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=flat&logo=react&logoColor=%2361DAFB) [![Node.js](https://img.shields.io/badge/Node.js-%23339933.svg?style=flat&logo=node.js&logoColor=white)](https://nodejs.org/) [![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-%23239120.svg?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML) [![Express.js](https://img.shields.io/badge/Express.js-%23000000.svg?style=flat&logo=express&logoColor=white)](https://expressjs.com/) [![Socket.IO](https://img.shields.io/badge/Socket.IO-%23000000.svg?style=flat&logo=socket.io&logoColor=white)](https://socket.io/) ![Amazon S3](https://img.shields.io/badge/Amazon%20S3-FF9900?style=flat&logo=amazons3&logoColor=white)  [![Docker](https://img.shields.io/badge/Docker-%232496ED.svg?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) 
</p>
</div>

## 📍 Overview

The MERN-Chat-App is a cutting-edge solution designed to streamline real-time communication. It leverages the MERN stack (MongoDB, Express.js, React, and Node.js) to offer a robust, scalable chat application. Key features include real-time communication with features like other trending social media applications and seamless integration with cloud services like AWS S3, Google Cloud's AI.

## 📸 Screenshots

<table>
  <tr>
    <td>
      <img src="screenshots/1_home.png" alt="Dark and Light Mode" width="400"/>
    </td>
    <td>
      <img src="screenshots/2_login_signup.png" alt="Authentication" width="400"/>
    </td>
  </tr>
  <tr>
    <td align="center">Dark/Light Mode and Responsive Website</td>
    <td align="center">Authentication</td>
  </tr>
  <tr>
    <td>
      <img src="screenshots/3_dashboard.png" alt="Responsive Dashboard" width="400"/>
    </td>
    <td>
      <img src="screenshots/4_newchat.png" alt="New Chat" width="400"/>
    </td>
  </tr>
  <tr>
    <td align="center">Responsive Dashboard</td>
    <td align="center">New Chat</td>
  </tr>
  <tr>
    <td>
      <img src="screenshots/5_searching.png" alt="Smooth Searching" width="400"/>
    </td>
    <td>
      <img src="screenshots/6_chatting_area.png" alt="Chatting Area" width="400"/>
    </td>
  </tr>
  <tr>
    <td align="center">Smooth Searching</td>
    <td align="center">Chatting Area & Real-time Communication</td>
  </tr>
  <tr>
    <td>
      <img src="screenshots/new_message.png" alt="New Message Notification" width="400"/>
    </td>
    <td>
      <img src="screenshots/typing_animation.png" alt="Typing Animation" width="400"/>
    </td>
  </tr>
  <tr>
    <td align="center">New Message Real-time Notification</td>
    <td align="center">Typing Animation</td>
  </tr>
  <tr>
    <td>
      <img src="screenshots/8_delete_message.png" alt="Message Management" width="400"/>
    </td>
    <td>
      <img src="screenshots/6_chatting_area.png" alt="Active Now Status" width="400"/>
    </td>
  </tr>
  <tr>
    <td align="center">Message Management</td>
    <td align="center">Active Now Status</td>
  </tr>
  <tr>
    <td>
      <img src="screenshots/6_chatting_area.png" alt="Message Seen Status" width="400"/>
    </td>
    <td>
      <img src="screenshots/personal_chatbot.png" alt="Personalized Chatbot" width="400"/>
    </td>
  </tr>
  <tr>
    <td align="center">Message Seen Status</td>
    <td align="center">Personalized Chatbot</td>
  </tr>
  <tr>
    <td>
      <img src="screenshots/7_send_photo.png" alt="Image Messages" width="400"/>
    </td>
    <td>
      <img src="screenshots/9_login_otp.png" alt="Login using OTP" width="400"/>
    </td>
  </tr>
  <tr>
    <td align="center">Image Messages</td>
    <td align="center">Login using OTP</td>
  </tr>
</table>

---
# Conversa-online-chatting-app
