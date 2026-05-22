# 💬 Real-Time Chat Application

A full-stack real-time chat application built using **MongoDB**, **Express**, **React**, and **Node.js** (MERN stack). This app allows users to communicate in real-time without page reloads, powered by **Socket.IO** for seamless, bi-directional WebSocket communication.

## 🚀 Features

- 🔒 User Authentication (assumed - please confirm)
- 💬 Real-time messaging with instant updates
- 🟢 Online/offline user status (if implemented)
- 📡 WebSocket communication via **Socket.IO**
- 🌐 RESTful APIs for user and chat data
- 🖥️ Responsive UI built with React

## 🛠️ Tech Stack

- **Frontend**: React
- **Backend**: Node.js + Express
- **Database**: MongoDB (via Mongoose)
- **Real-Time Engine**: Socket.IO
- **Runtime**: Node.js

## 📁 Folder Structure

```bash
/Client 👉React frontend
/server 👉Express backend with API and Socket.IO
```
---


## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/mp-lp/Chat-application.git
cd Chat-application
```
### 2. Set Up the Backend
```bash
cd server
npm install
```
Create a .env file in /server with necessary variables:
```bash
MONGO_URI=your_mongodb_connection_string
PORT=5000
```
---
### 3. Set Up the Frontend
```bash
cd ../client
npm install
```
### 4. Run the Application
Start Backend
```bash
cd ../server
npm start
```
Start Frontend
```bash
cd ../Client
npm run dev
```
The frontend will usually run on http://localhost:3000, and backend on http://localhost:5000.


