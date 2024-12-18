# BlockGPT - AI Chatbot for Blockchain Domain

BlockGPT is an advanced chatbot specifically designed for the blockchain domain. It utilizes GPT-3.5 Architecture and Langchain LLM to provide comprehensive responses to blockchain-related queries.

## Features

- Google Authentication integration
- Real-time chat interface
- Session management
- Chat history tracking
- Custom AI responses for blockchain-related queries
- Responsive web design

## Tech Stack

- Frontend: React.js
- Backend: Flask (Python)
- AI: GPT-3.5, Langchain LLM
- Database: MongoDB
- Authentication: Google OAuth

## Prerequisites

- Node.js and npm
- Python 3.x
- MongoDB instance
- API keys for OpenAI, CoinMarketCap, and other services

## Environment Variables

Create a `.env` file in the server directory with the following variables:

```
CMC_KEY = "Your CoinMarketCap API Key"
ITB_KEY = "Your ITB API Key"
OPEN_AI = "Your OpenAI API Key"
MONGO_URI = "Your MongoDB Connection String"
FLASK_DEBUG = True
```

## Installation

### Client Setup
```bash
cd client
npm install
npm start
```

### Server Setup
```bash
cd server
pip install -r requirements.txt
python Langchain_V1.py
```

## Running the Application

1. Start the server:
   ```bash
   cd server
   python Langchain_V1.py
   ```

2. In a separate terminal, start the client:
   ```bash
   cd client
   npm start
   ```

3. Access the application at `http://localhost:3000`

## Current Status

The application is currently in alpha stage (α2.0) and runs locally. Known limitations:
- Some bugs in the build need to be addressed
- Chat history feature needs enhancement
- Timestamps for user interactions to be implemented
- Integration with company website pending

## Future Improvements

- Bug fixes and stability improvements
- Enhanced user experience and design
- Expanded data collection from crypto websites
- Integration with company website
- Additional functionalities including:
  - Improved chat history storage
  - Timestamp display for interactions
  - Enhanced session management
