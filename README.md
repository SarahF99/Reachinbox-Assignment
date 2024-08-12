# Reachinbox-Assignment
Reachinbox Web App
This is a functional web application created as an assignment. The app includes a login page, a onebox screen, API integration, custom keyboard shortcuts, a custom text editor, and both light and dark modes.

# Table of Contents:
Features
Prerequisites
Installation
Running the Project Locally
Usage
Keyboard Shortcuts
API Endpoints
Customization
Acknowledgements

# Features
Google Login integration.
Fetch and display data from API endpoints.
Custom keyboard shortcuts in the onebox screen.
Custom text editor with "SAVE" and "Variables" buttons.
Light and dark mode switch.
Responsive and modern design based on Figma file.

# Prerequisites
Before you begin, ensure you have met the following requirements:

Node.js (version 12 or higher) installed on your local machine.
Git installed on your local machine.
A code editor like Visual Studio Code or Sublime Text.

# Installation
To get a local copy of the project up and running, follow these steps:

Clone the Repository:

bash
Copy code
git clone https://github.com/SarahF99/Reachinbox-Assignment.git
Navigate to the Project Directory:

bash
Copy code
cd reachinbox-webapp
Install Dependencies:

If your project includes any Node.js dependencies (like express.js), run:

bash
Copy code
npm install
If there are no dependencies, you can skip this step.

# Running the Project Locally
To run the project locally, follow these steps:

Open the Project in Your Code Editor:

Open the cloned repository in your preferred code editor (e.g., Visual Studio Code).

Start a Local Server:

If you're using Node.js with express:

bash
Copy code
npm start
If the project is purely front-end, you can open the index.html file directly in your browser or use an extension like "Live Server" in Visual Studio Code:

Live Server: Right-click on index.html and select "Open with Live Server".
Access the Application:

If using a Node.js server, open your browser and go to http://localhost:3000 (or the port specified in your server).
If using Live Server or directly opening the index.html, the browser will open automatically.

# Usage
Login:

Click the "Login" button to authenticate with Google.
After successful login, you will be redirected to the onebox screen.
Interact with the Onebox:

View threads fetched from the API.
Use keyboard shortcuts to delete or reply to threads.
Use the custom text editor to compose and send replies.
Switch Themes:

Toggle between light and dark mode using the switch provided on the onebox screen.

# Keyboard Shortcuts
D: Delete the selected thread.
R: Open the Reply box for the selected thread.

# API Endpoints
The following API endpoints are used in this project:

GET /onebox/list: Fetches the list of threads.
GET /onebox/
: Fetches details of a specific thread.
DELETE /onebox/
: Deletes a specific thread.
POST /reply/
: Sends a reply to a specific thread.

# Customization
Styling: Modify the styles.css file to change the look and feel of the app.
JavaScript Functionality: Edit the script.js and onebox.js files to adjust functionality, keyboard shortcuts, and API interactions.

# Acknowledgements
Design inspiration from the Figma file provided in the assignment.
API documentation provided by the assignment.
