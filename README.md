# 🤖 Basic ADK Agent: Greeting Agent Example

## 🎯 Overview
This project contains the most basic implementation of an AI agent using the **Google Agent Development Kit (ADK)**. 

The agent, named `greeting_agent`, is configured to use the `gemini-2.0-flash` model and is instructed to initiate a conversation by asking the user's name and then greeting them.

---

## ⚙️ Project Setup

Follow these steps to set up the environment and install dependencies.

### 1. Clone the Repository
If you are cloning this project onto a new machine, use the Git clone command.

### 2. Create and Activate the Virtual Environment
Navigate to the root directory of this project (`ADK-Course`) and run these commands to create and activate the isolated Python environment.

```bash

python -m venv .venv

.venv\Scripts\Activate.ps1

3. Install Dependencies
Install the required packages (Google ADK, python-dotenv) using the requirements.txt file.

# Ensure the .venv environment is active before running
pip install -r requirements.txt

This is the recommended README.md file based on the structure and content of the "Basic Agent" example from the Agent Development Kit (ADK) Crash Course.

You can create a new file named README.md in the root of your project (ADK-Course folder) and paste the content below:

Markdown

# 🤖 Basic ADK Agent: Greeting Agent Example

## 🎯 Overview
This project contains the most basic implementation of an AI agent using the **Google Agent Development Kit (ADK)**. 

The agent, named `greeting_agent`, is configured to use the `gemini-2.0-flash` model and is instructed to initiate a conversation by asking the user's name and then greeting them.

---

## ⚙️ Project Setup

Follow these steps to set up the environment and install dependencies.

### 1. Clone the Repository
If you are cloning this project onto a new machine, use the Git clone command.

### 2. Create and Activate the Virtual Environment
Navigate to the root directory of this project (`ADK-Course`) and run these commands to create and activate the isolated Python environment.

```bash
# Create the virtual environment
python -m venv .venv

# Activate the environment (for Windows PowerShell)
.venv\Scripts\Activate.ps1
3. Install Dependencies
Install the required packages (Google ADK, python-dotenv) using the requirements.txt file.

Bash

# Ensure the .venv environment is active before running
pip install -r requirements.txt
🔑 Set Up API Key
This project requires a Gemini API Key. Since the .env file is excluded from Git for security, you must create it manually.

1.Get your API key from Google AI Studio.

2.Navigate to the greeting-agent folder.

3.Create a new file named .env inside the greeting-agent folder.

4.Add your key inside the file:

Code snippet

GOOGLE_API_KEY="YOUR_ACTUAL_API_KEY_HERE"


This is the recommended README.md file based on the structure and content of the "Basic Agent" example from the Agent Development Kit (ADK) Crash Course.

You can create a new file named README.md in the root of your project (ADK-Course folder) and paste the content below:

Markdown

# 🤖 Basic ADK Agent: Greeting Agent Example

## 🎯 Overview
This project contains the most basic implementation of an AI agent using the **Google Agent Development Kit (ADK)**. 

The agent, named `greeting_agent`, is configured to use the `gemini-2.0-flash` model and is instructed to initiate a conversation by asking the user's name and then greeting them.

---

## ⚙️ Project Setup

Follow these steps to set up the environment and install dependencies.

### 1. Clone the Repository
If you are cloning this project onto a new machine, use the Git clone command.

### 2. Create and Activate the Virtual Environment
Navigate to the root directory of this project (`ADK-Course`) and run these commands to create and activate the isolated Python environment.

```bash
# Create the virtual environment
python -m venv .venv

# Activate the environment (for Windows PowerShell)
.venv\Scripts\Activate.ps1
3. Install Dependencies
Install the required packages (Google ADK, python-dotenv) using the requirements.txt file.

Bash

# Ensure the .venv environment is active before running
pip install -r requirements.txt
🔑 Set Up API Key
This project requires a Gemini API Key. Since the .env file is excluded from Git for security, you must create it manually.

Get your API key from Google AI Studio.

Navigate to the greeting-agent folder.

Create a new file named .env inside the greeting-agent folder.

Add your key inside the file:

Code snippet

GOOGLE_API_KEY="YOUR_ACTUAL_API_KEY_HERE"
▶️ Running the Agent
Run the adk web command from the root directory of your project (ADK-Course) to launch the interactive developer UI.

Bash

# Run this from the root folder containing the 'greeting-agent' subdirectory
adk web greeting-agent
Access the web interface at the provided local URL (usually http://127.0.0.1:8000/dev-ui/).

Select greeting_agent from the dropdown menu in the top-left corner.

Type a message to start interacting with your agent!
