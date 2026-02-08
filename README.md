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
Ensure your project follows this structure:

ai-chatbot/
├── app.py              # Main Flask application
├── .env                # Environment variables
├── database.db         # SQLite database (auto-generated)
├── templates/          # HTML templates
│   ├── index.html      # Chat interface
│   ├── login.html      # Login page
│   └── signup.html     # Registration page
└── requirements.txt    # Project dependencies

### Usage
Start the Flask server
``` bash
python app.py
```

Open the application

Navigate to the following URL in your browser:
```

http://127.0.0.1:5000
```

Getting Started

1.Go to the Sign Up page and create a new account
2.Log in using your credentials
3.Enter your message in the chat input field
4.Press Enter or click Send

Configuration

Create a .env file in the root directory and add the following:
```
API_KEY=your_ai_api_key_here
SECRET_KEY=your_random_secret_string_here
```




Project Structure Explained

app.py – Handles routing, authentication, and chatbot logic

database.db – Stores user credentials securely

templates/ – Contains HTML files for UI pages

requirements.txt – Lists all Python dependencies

.env – Stores sensitive keys and secrets

Contributing

Contributions are welcome and encouraged.

Report Bugs: Use the GitHub Issues tab

Follow Standards: Write clean code following PEP 8

Pull Requests:

Create a separate branch for each feature

Clearly describe the changes made

License

This project is licensed under the MIT License and is free to use and modify.

Contact and Support

For help or questions:

Use the project’s issue tracker

Refer to this README for setup and troubleshooting guidance