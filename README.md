# Backend API – JobGenie

This is the backend API for the JobGenie application. It uses Node.js, Express, and PostgreSQL to provide data services for resume analysis and job-matching features.

## 🚀 Technologies Used

- Node.js  
- Express.js  
- PostgreSQL  
- pg (PostgreSQL client for Node)  
- dotenv  

## 📁 Project Structure

backend/
├── .env # Environment variables (excluded from Git)

├── .gitignore # Git ignore settings

├── index.js # Main server file

├── queries.js # PostgreSQL database connection

├── package.json # Node dependencies

└── README.md # Project documentation


## 🔐 Environment Variables

Make sure to create a `.env` file in the root of your backend directory. Here's the format:

DB_NAME=api
DB_USERNAME=me
DB_HOST=localhost
DB_PASSWORD=password
DB_PORT=5432


> **Important:** This file is excluded from version control via `.gitignore`.

## 💻 Getting Started

**1. Clone the repo:**


```bash
git clone https://github.com/Mustak-Eman/Backend.git
npm install
node index.js

