Node Chat
===========

This is an application for chat built with node.js and Express.

---

## Features
- Material Design Interface
- Emoji functionality
- User @mention capability
- Private message exchange
- Message removal (for admins)
- Power to kick/ban users (for admins)

#### There are 3 admin levels:
- **Helper:** Can remove chat messages
- **Moderator:** The above plus the power to kick and ban users
- **Administrator:** All the above plus broadcast global alerts and promote/demote users

---

## Usage
After you clone this repo to your desktop, go to its root directory and run `npm install` to install its dependencies.

Once the dependencies are installed, you can run  `npm start` to start the application. You will then be able to access it at localhost:3000

To give yourself administrator permissions on the chat, you will have to type `/role [your-name]` in the app console.