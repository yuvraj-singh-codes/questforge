# QuestForge ![Build Status](https://img.shields.io/badge/build-passing-brightgreen) ![Version](https://img.shields.io/badge/version-1.0.0-blue)

## Project Description
QuestForge is a web application that allows players to create, share, and embark on custom quests in their favorite games. Utilizing AI and advanced data storage, players can generate quests tailored to their interests and collaborate with friends to enhance their gaming experience.

## Features
- 🎮 Dynamic quest generation based on player preferences
- 🤝 Real-time collaboration for multiplayer quest creation
- 🗣️ Integration with AI-driven NPC dialogue systems

## Tech Stack
### Frontend
- React.js

### Backend
- FastAPI
- Langchain

### Database
- QdrantDB
- Pinecone

## Installation
To set up QuestForge locally, follow these steps:

- Clone the repository:
  bash
  git clone https://github.com/yuvraj-singh-codes/questforge
  - Navigate to the project directory:
  bash
  cd questforge
  - Install the required dependencies:
  bash
  pip install -r requirements.txt
  - Install frontend dependencies:
  bash
  cd frontend
  npm install
  - Start the backend server:
  bash
  uvicorn main:app --reload
  - Start the frontend application:
  bash
  npm start
  ## Usage
Once the application is running, navigate to `http://localhost:3000` in your web browser to access QuestForge. From there, you can create quests, collaborate with friends, and explore AI-driven NPC dialogues.

## API Documentation
For detailed API documentation, please refer to the [API Documentation](https://github.com/yuvraj-singh-codes/questforge/wiki/API-Documentation).

## Testing
To run the tests for QuestForge, execute the following command in the project directory:

bash
pytest
## Deployment
For deploying QuestForge, follow these steps:

- Build the frontend application:
  bash
  cd frontend
  npm run build
  - Deploy the backend using your preferred cloud service (e.g., AWS, Heroku).

## Contributing
We welcome contributions to QuestForge! Please follow these guidelines:

- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and commit them with clear messages.
- Push your branch and create a pull request.

Thank you for your interest in contributing to QuestForge!