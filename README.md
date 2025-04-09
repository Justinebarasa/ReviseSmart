ReviseSmart - Learn Smart, Succeed Bright
ReviseSmart is a high school revision website designed to support students following the Kenyan secondary school curriculum (8-4-4 system). The platform provides a user-friendly interface for accessing revision resources, with features like subject exploration, contact forms, and an about page. It includes user authentication to ensure resources are accessible only to registered users.

Features
Front-End:
Responsive design with HTML, CSS, and vanilla JavaScript.
Pages: Home (index.html), Subjects (subjects.html), About (about.html), Contact (contact.html).
User authentication modals for signup and login.
Dynamic content visibility based on login status.
Back-End:
Built with Node.js and Express.js.
MongoDB integration for user data storage.
API endpoints for signup, login, and login status checks.
Security:
Simulated authentication (extendable to JWT or sessions).
Protected routes redirect unauthenticated users to the home page.
Tech Stack
Front-End: HTML5, CSS3, JavaScript (vanilla)
Back-End: Node.js, Express.js
Database: MongoDB (via Mongoose)
Dependencies: express, mongoose, cors, body-parser
Prerequisites
Node.js and npm: Download
MongoDB: Install
A modern web browser (e.g., Chrome, Firefox)
Setup Instructions
1. Clone or Download the Project
Clone this repository or download the files into a local directory:
bash

Collapse

Wrap

Copy
git clone <repository-url> revisesmart
cd revisesmart
2. Install Back-End Dependencies
Navigate to the project root:
bash

Collapse

Wrap

Copy
npm install
This installs express, mongoose, cors, and body-parser.
3. Set Up MongoDB
Ensure MongoDB is installed and running:
Check version:
bash

Collapse

Wrap

Copy
mongod --version
Start MongoDB:
bash

Collapse

Wrap

Copy
mongod
If it fails, specify a data directory: mongod --dbpath ~/data/db (create ~/data/db first with mkdir -p ~/data/db).
Leave the terminal open to keep MongoDB running.
4. Start the Express Server
In a new terminal, from the revisesmart directory:
bash

Collapse

Wrap

Copy
node server/server.js
Expected output:
text

Collapse

Wrap

Copy
Server running on http://localhost:3000
MongoDB connected successfully
5. Access the Website
Open a browser and go to:
text

Collapse

Wrap

Copy
http://localhost:3000/index.html
Sign up or log in to access protected pages (Subjects, About, Contact).
