# RealChat AI – Real-Time Chatroom with AI Assistant

A real-time chatroom web app powered by Socket.IO and integrated with an AI assistant to respond to user messages.

## 👨‍👩‍👧‍👦 Team Members

- Can – Frontend & UI/UX
- Ella, Resya – Backend & Database
- Fahri – AI Integration


## 🚀 Tech Stack

### Frontend

- React + Vite
- React Router
- React Context (State Management)
- Socket.IO-client

### Backend

- Express.js
- Sequelize (PostgreSQL)
- Socket.IO
- OpenAI/Gemini API (AI Assistant)

## 📦 Features

- Real-time chatroom (multiple users)
- Auto-reply AI assistant inside the chatroom
- Store chat history (user + AI)
- Optional multi-room support
- Responsive UI

## 🧠 How It Works

- User joins the chatroom → sends message via socket
- Server receives message → stores to DB → emits to all clients
- If message is from human, server sends it to AI API and emits response as `isBot = true`

## 🛠️ Setup

### 1. Clone & Install

```bash
git clone https://github.com/CanSaragih/ChatVerse-P2.git
```
