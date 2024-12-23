Royal Flavours Dhaba Chatbot 🌟🍽️
<p align="center"> <img src="https://via.placeholder.com/800x400?text=Royal+Flavours+Chatbot+Demo" alt="Chatbot Demo" width="80%"/> </p>
📖 Project Overview
The Royal Flavours Dhaba Chatbot is a fully automated food ordering assistant, designed to simplify and streamline the process of ordering delicious meals from Royal Flavours Dhaba.
Built using Google Dialogflow, FastAPI, and MySQL, this chatbot supports:

🛒 Adding items to orders
🗑️ Removing items from orders
📦 Tracking order status
✔️ Completing orders seamlessly
✨ Key Features
Dialogflow-powered Natural Language Understanding: Seamlessly processes user inputs and provides appropriate responses.
FastAPI Backend: Handles webhook requests, processes user data, and manages order flow.
MySQL Integration: Manages order data and tracks order statuses with stored procedures.
User-Friendly Flow: Supports editing, tracking, and confirming orders interactively.
🚀 Tech Stack
Frontend: Chatbot UI components or web integration.
Backend: Python-based FastAPI for request handling.
Database: MySQL for data storage and management.
Cloud: Google Dialogflow for conversation logic.
🛠️ Installation Guide
Clone the repository:

bash
Copy code
git clone https://github.com/Ishit-024/Royal-Flavors-Dhaba_Chatbot.git
Navigate to the backend folder and install dependencies:

bash
Copy code
cd backend
pip install -r requirements.txt
Configure the database: Update the db_helper.py file with your MySQL credentials.

Run the FastAPI server:

bash
Copy code
uvicorn main:app --reload
Set up Dialogflow Webhook: Set the webhook URL to:

arduino
Copy code
http://<your_server_ip>:8000/
Access the frontend: Ensure the frontend folder is served using a hosting platform or a local server.

📷 Screenshots
1. Chatbot in Action:
<p align="center"> <img src="https://via.placeholder.com/600x300?text=Chatbot+Demo" alt="Chatbot Demo" width="70%"/> </p>
2. Backend Architecture:
<p align="center"> <img src="https://via.placeholder.com/600x300?text=Backend+Architecture" alt="Backend Architecture" width="70%"/> </p>
🌐 API Endpoints
POST / - Webhook endpoint to handle Dialogflow requests.
🗂️ Folder Structure
plaintext
Copy code
.
├── backend
│   ├── main.py           # FastAPI server
│   ├── db_helper.py      # Database operations
│   ├── generic_helper.py # Utility functions
├── frontend
│   └── index.html        # Chatbot UI
└── README.md             # Project documentation
