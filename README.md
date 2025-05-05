# 💬 ChatVerse

A real-time web chatroom enhanced with AI Assistant. Communicate instantly with your team and interact with an intelligent assistant that can answer questions, provide suggestions, or just chat with you — all in one place.

---

## 📘 Application Overview

**ChatVerse** is a real-time chatroom web application that enables users to communicate instantly within a shared chat space. It includes a built-in **AI Assistant** that responds to user queries, providing helpful suggestions or simply acting as a smart chatbot.

Built with **React (Vite)** and **Socket.IO**, ChatVerse uses **React Context** for managing global state and integrates with AI APIs (OpenAI/Gemini) for intelligent conversations.

---

## 🎨 Application Theme

**Real-Time Communication with AI-Enhanced Interaction**

The app merges two core concepts:
- Real-time messaging between multiple users
- AI-enhanced interaction for smarter communication

---

## 🚀 Main Features

### 💬 Real-Time Chat Communication
- Instant message delivery using **Socket.IO**
- Live updates when users join/leave or are typing

### 🤖 AI Assistant Integration
- An AI-powered assistant (`@Assistant`) that can:
  - Answer questions
  - Recommend movies, books, or food
  - Help with coding/tech issues
- Powered by Gemini or OpenAI API

### 👥 Multi-User Chatroom
- Users can log in with a nickname and join the room
- Online users are tracked and displayed in real-time

### 🧠 React Context for State Management
- Stores chat logs, user info, and UI state efficiently
- Shared state across components without prop-drilling

### 🌐 SPA (Single Page Application)
- Seamless navigation using **React Router**
- Clean separation between Login and Chatroom page

---

## 🛠️ Tech Stack

- **Client**: React + Vite, React Context, React Router
- **Realtime**: Socket.IO (client & server)
- **AI Integration**: OpenAI API or Google Gemini
- **Deployment**: Netlify / Vercel (Client), Render (Optional Server)

---

## 📦 Getting Started

```bash
# Clone the repo
git clone https://github.com/your-username/chatverse.git

# Install dependencies
cd client
npm install

# Run the client
npm run dev
