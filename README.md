# 🎓 Teacher & Researcher Portal - Setup Guide

This guide will help you get the project running on your computer after downloading the files.

---

## 🚀 Step-by-Step Instructions

### 1. Unzip the Folder
After downloading, right-click the ZIP file and select **"Extract All"**. 
*Note: The code will not run correctly if you try to open it from inside the "Compressed" view.*

### 2. Setup the Backend (The Server)
1. Open your terminal (or Command Prompt) and move into the `backend` folder:
   ```bash
   cd path/to/backend
Install the necessary libraries:

Bash
npm install

Create a .env file inside the backend folder.

Open that file in Notepad and paste the link I sent you:

something like this
MONGO_URI=mongodb+srv://admin:password123@cluster0...

Start the server:

Bash
node server.js

3. Setup the Frontend (The Website)
Open a SECOND terminal window and go to the frontend folder:

Bash
cd path/to/frontend
Install the libraries:

Bash
npm install
Start the website:

Bash
npm start
