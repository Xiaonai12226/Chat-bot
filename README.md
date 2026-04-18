# Ivy Chatbot System

The Ivy Chatbot System is a comprehensive multi-bot framework that supports various types of chatbots, each tailored to specific functionalities. This documentation provides an overview of the system components and configuration options.

## Features
- Multi-bot support
- Customizable bot profiles
- Easy integration with MongoDB
- Frontend built with React

## Structure
- `server/`: Contains the backend code including API routes, database models, and bot configurations.
- `client/`: Contains the frontend code, which is built using React.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/<USERNAME>/Chat-Bot.git
   cd Chat-Bot
   ```
2. Install dependencies for server and client:
   ```bash
   cd server && npm install
   cd ../client && npm install
   ```
3. Set up environment variables in a `.env` file based on the `.env.example` template.
4. Start the server:
   ```bash
   cd server
   node server.js
   ```
5. Start the client:
   ```bash
   cd client
   npm start
   ```

## Configuration
- Update `server/config/db.js` with your MongoDB connection string.
- Configure bot profiles in the respective JSON files within `server/config/bots/`.

## Usage
- Access the client application via `http://localhost:3000`.
- Use the chat interface to interact with the bots defined in your configuration.

## Contribution
Feel free to contribute by creating a pull request or opening an issue for discussions.