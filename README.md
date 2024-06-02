Set Up the Environment
First, set up a virtual environment and install the required packages.

mkdir chat-app
cd chat-app
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install flask flask-socketio

chat-app/
│
├── venv/                   # Virtual environment directory
├── app.py                  # Flask application
└── templates/              # HTML templates
    └── index.html          # Frontend HTML file


Run Flask Application:
In this project directory, run the Flask application:

python app.py

Example of Testing the Chat Application
Open Tab 1:

Navigate to http://127.0.0.1:5000.
You will see the chat interface.
Open Tab 2:

Open another tab in the same browser or a different browser and navigate to http://127.0.0.1:5000.
Send a Message from Tab 1:

Type "Hello from Tab 1!" in the input box and click "Send" or press Enter.
The message "Hello from Tab 1!" should appear in the message area of both Tab 1 and Tab 2.
Send a Message from Tab 2:

Type "Hello from Tab 2!" in the input box and click "Send" or press Enter.
The message "Hello from Tab 2!" should appear in the message area of both Tab 1 and Tab 2.
