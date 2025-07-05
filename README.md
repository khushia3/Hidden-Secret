# Hidden-Secret
A simple Express.js app that fetches and displays a random secret and its author from a public API using Axios and EJS. Built for learning how to consume APIs, render dynamic content, and serve static assets.


📸 Preview
"Sometimes all you need is a secret from a stranger... 🤫"



🚀 Features
Fetches a random secret from https://secrets-api.appbrewery.com/random

Displays the secret and the username of the anonymous user

Renders the data on an EJS template

Serves static files using the public folder


🧰 Tech Stack
Tool	Purpose
Node.js	JavaScript runtime
Express.js	Web framework
Axios	HTTP client for API requests
EJS	Template engine for rendering views
HTML/CSS	UI design (inside public/)



⚙️ How to Run

1. Clone the repository

git clone https://github.com/your-username/secrets-app.git
cd secrets-app

2. Install dependencies

npm install

3. Run the server

node index.js
or with auto-reload: 
nodemon index.js

4. Open in browser
Visit http://localhost:3000


📦 Sample Output (from API)
{
  "secret": "I sometimes dance in the elevator when no one is watching.",
  "username": "elevatorWhisperer"
}


✨ Future Improvements
Add a button to fetch a new secret without refreshing

Allow users to submit their own secrets

Store secrets locally in a file or database

Add styling with Tailwind or Bootstrap

