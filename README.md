# Professor_AI
# Professor AI Setup (Mac M2)

## Requirements

Install:

* Ollama
* Python 3
* Node.js
* FFmpeg

## Setup

### 1. Clone the project

git clone https://github.com/yourname/professor-ai.git
cd professor-ai

### 2. Install backend

cd backend
pip3 install -r requirements.txt

### 3. Install frontend

cd ../frontend/nextjs_app
npm install

### 4. Install AI models

ollama pull llama3.1:8b
ollama pull nomic-embed-text

### 5. Run the app

Start backend:

cd ../../backend
python3 app.py

Start frontend:

cd ../frontend/nextjs_app
npm run dev

Open:

http://localhost:3000

## Features

* YouTube video & playlist learning
* File upload (PDF, TXT, DOCX, images)
* ChatGPT-style conversation history
* Fully offline AI using Ollama
