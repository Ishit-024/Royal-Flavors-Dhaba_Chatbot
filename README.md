<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Royal Flavours Dhaba Chatbot</title>
</head>
<body style="font-family: Arial, sans-serif; line-height: 1.6; margin: 20px;">

    <h1 style="text-align: center; color: #4CAF50;">🌟 Royal Flavours Dhaba Chatbot 🍽️</h1>

    <p align="center">
        <img src="https://via.placeholder.com/800x400?text=Royal+Flavours+Chatbot+Demo" alt="Chatbot Demo" style="border-radius: 10px; max-width: 100%;"/>
    </p>

    <h2>📖 Project Overview</h2>
    <p>
        The <b>Royal Flavours Dhaba Chatbot</b> is a fully automated food ordering assistant, designed to simplify and streamline the process of ordering delicious meals from <i>Royal Flavours Dhaba</i>. 
        Built using <b>Google Dialogflow</b>, <b>FastAPI</b>, and <b>MySQL</b>, this chatbot supports:
        <ul>
            <li>🛒 Adding items to orders</li>
            <li>🗑️ Removing items from orders</li>
            <li>📦 Tracking order status</li>
            <li>✔️ Completing orders seamlessly</li>
        </ul>
    </p>

    <h2>✨ Key Features</h2>
    <ul>
        <li><b>Dialogflow-powered Natural Language Understanding:</b> Seamlessly processes user inputs and provides appropriate responses.</li>
        <li><b>FastAPI Backend:</b> Handles webhook requests, processes user data, and manages order flow.</li>
        <li><b>MySQL Integration:</b> Manages order data and tracks order statuses with stored procedures.</li>
        <li><b>User-Friendly Flow:</b> Supports editing, tracking, and confirming orders interactively.</li>
    </ul>

    <h2>🚀 Tech Stack</h2>
    <ul>
        <li><b>Frontend:</b> Designed to integrate with chatbot platforms or UI components (if applicable).</li>
        <li><b>Backend:</b> Python-based <b>FastAPI</b> for handling requests.</li>
        <li><b>Database:</b> MySQL for order storage and management.</li>
        <li><b>Cloud:</b> Google Dialogflow for chatbot logic and conversation flow.</li>
    </ul>

    <h2>🛠️ Installation Guide</h2>
    <ol>
        <li><b>Clone this repository:</b></li>
        <pre><code>git clone https://github.com/Ishit-024/Royal-Flavors-Dhaba_Chatbot.git</code></pre>

        <li><b>Navigate to the backend folder and install dependencies:</b></li>
        <pre><code>cd backend
pip install -r requirements.txt</code></pre>

        <li><b>Configure the database:</b></li>
        <p>Update the <code>db_helper.py</code> file with your MySQL credentials.</p>

        <li><b>Run the FastAPI server:</b></li>
        <pre><code>uvicorn main:app --reload</code></pre>

        <li><b>Connect Dialogflow to the webhook:</b></li>
        <p>Set the webhook URL to <code>http://<your_server_ip>:8000/</code>.</p>

        <li><b>Access the frontend:</b></li>
        <p>Ensure the frontend folder is served by your preferred hosting platform or local server.</p>
    </ol>

    <h2>📷 Screenshots</h2>
    <p>
        <b>1. Chatbot in Action:</b><br>
        <img src="https://via.placeholder.com/600x300?text=Chatbot+Demo" alt="Chatbot Demo" style="border-radius: 10px; max-width: 100%;"/>
    </p>
    <p>
        <b>2. Backend Architecture:</b><br>
        <img src="https://via.placeholder.com/600x300?text=Backend+Architecture" alt="Backend Architecture" style="border-radius: 10px; max-width: 100%;"/>
    </p>

    <h2>🌐 API Endpoints</h2>
    <ul>
        <li><code>POST /</code> - Webhook endpoint to handle Dialogflow requests.</li>
    </ul>

    <h2>🗂️ Folder Structure</h2>
    <pre><code>.
├── backend
│   ├── main.py          # FastAPI server
│   ├── db_helper.py     # Database operations
│   ├── generic_helper.py # Utility functions
├── frontend
│   └── index.html       # Chatbot UI
└── README.md            # Project documentation
</code></pre>

    <h2>🙌 Acknowledgments</h2>
    <ul>
        <li><b>Codebasics YouTube Channel</b> - Inspiration and foundational concepts for this project.</li>
    </ul>

    <h2>📬 Contact</h2>
    <p>
        Have questions or suggestions? Feel free to reach out:
        <ul>
            <li><b>Email:</b> ish***@gmail.com</li>
            <li><b>GitHub:</b> <a href="https://github.com/Ishit-024">Ishit-024</a></li>
        </ul>
    </p>

    <footer style="text-align: center; margin-top: 50px;">
        <p>🛠️ Made with ❤️ by <b>Ishit</b> for Royal Flavours Dhaba 🍴</p>
    </footer>

</body>
</html>
