# project1
# User Registration with Validation

A simple user registration system using AngularJS (frontend), Node.js + Express (backend), and MySQL (database).

##  Features

- AngularJS template-driven form
- Real-time validation
- Email pattern check
- Password and confirm password match
- API call to backend with validation
- User data stored in MySQL

## Technologies

- AngularJS 1.x
- Node.js + Express
- MySQL
- HTML/CSS

##  Setup Guide

###  Backend

1. Install dependencies:
```bash
cd backend
npm install
•	configure MySQL database:
o	Log into MySQL and run:
CREATE DATABASE userdb;

USE userdb;

CREATE TABLE users (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(100),
  email VARCHAR(100) UNIQUE,
  password VARCHAR(255)
);
•	Update database credentials in server.js if necessary.
•	Start the backend server:
node server.js
Server runs on http://localhost:3000
3. Frontend Setup
•	Navigate to the frontend folder.
•	Serve files using any static server (e.g., Live Server in VS Code) or open index.html in a browser.
## Setup Guide

### 1. Clone the repository
```bash
git clone https://github.com/Darice1234/project1
cd project1

