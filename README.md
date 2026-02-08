# AI Chatbot with Flask Authentication

A professional, high-performance AI chatbot application built with **Python** and **Flask**.  
This project includes a secure user authentication system and a modern, dark-themed user interface, and is designed to integrate with **any AI or Large Language Model (LLM) API**.

---

## Description

This project serves as both a starter template and a complete standalone application for building an AI-powered chat tool. It enhances a basic chatbot by adding real-world features such as user authentication, persistent sessions, and a polished frontend.

The AI layer is flexible and can be connected to any external AI API, making the project adaptable to multiple platforms and models.

---

## Features

- **AI-Powered Chat**  
  Supports integration with any AI or LLM API for generating intelligent responses.

- **User Authentication**  
  Secure Sign-Up and Login functionality using **Flask-Login**.

- **Persistent User Sessions**  
  Maintains user login state across page refreshes using cookies.

- **Modern UI**  
  ChatGPT-style dark theme with responsive layout and alternating chat bubbles.

- **Optimized Output**  
  Configurable prompts and response limits for concise and meaningful interactions.

---

## Prerequisites

Ensure the following are installed before starting:

- **Python** 3.8 or higher  
- **VS Code** (recommended) or any modern code editor  
- **AI API Key** (optional until AI integration is implemented)

---

## Installation

Follow the steps below to set up the project locally.

### Step 1: Create the project directory
```bash
mkdir ai-chatbot
cd ai-chatbot
```

### Step 2:Install required dependencies
```bash
pip install flask flask-sqlalchemy flask-login python-dotenv
```

### Step 3:Project file structure

## Project File Structure

ai-chatbot/
├── app.py              - Main Flask application  
├── .env                - Environment variables  
├── database.db         - SQLite database (auto-generated)  
├── templates/          - HTML templates  
│   ├── index.html      - Chat interface  
│   ├── login.html      - Login page  
│   └── signup.html     - Registration page  
└── requirements.txt    - Python dependencies  

## How to Run the Project

1. Install the required dependencies using `requirements.txt`
2. Start the Flask server by running:
``` python app.py```
3. Open your browser and go to:
http://127.0.0.1:5000


## Application Usage

- Navigate to the Sign Up page and create a new account  
- Log in using your registered credentials  
- Enter a message in the chat input field  
- Press Enter or click the Send button to interact with the chatbot  

## Environment Configuration

Create a `.env` file in the root directory and add:
```API_KEY=your_ai_api_key_here
SECRET_KEY=your_random_secret_string_here
``` 

Note:
- Do not share the `.env` file
- Do not upload it to public repositories

## File Description

- `app.py` handles routing, authentication, and chatbot logic  
- `database.db` stores user data securely  
- `templates` contains all frontend HTML pages  
- `requirements.txt` lists required Python libraries  
- `.env` stores sensitive configuration values  

## Contribution Guidelines

- Report issues using the GitHub Issues section  
- Follow PEP 8 coding standards  
- Create separate branches for new features  
- Clearly explain changes in pull requests  

## License

This project is licensed under the MIT License.

## Support

For any issues or queries, refer to this README or use the project issue tracker.




