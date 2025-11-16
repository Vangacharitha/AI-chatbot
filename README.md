🤖 n8n-Automation-AI-Mentor-Chatbot
AI Mentor Chatbot using n8n, Google Gemini & Telegram

This repository contains a fully automated AI Mentor Chatbot built using n8n, Google Gemini LLM, and the Telegram Bot API.
The chatbot helps students ask technical doubts related to Python, EDA, Machine Learning, and Deep Learning and receive instant AI-generated explanations — with session memory and without writing any backend code.

📸 Workflow Snapshot

AI Mentor Chatbot Workflow (n8n Editor View)

<img width="1915" height="844" alt="AI chatbot" src="https://github.com/user-attachments/assets/3f8f2f3e-3234-496b-9577-3ee6e7626aba" />


🚀 Key Features

⚡ Real-time AI responses for student questions

🧠 Gemini-powered natural language understanding

🔄 Simple Memory node to maintain conversation context

📲 Telegram integration for instant messaging

🔧 No traditional backend needed — everything runs inside n8n

🧩 Modular workflow, easy to customize or extend

🎓 Specialized for EdTech & student doubt resolution

🧩 Workflow Overview

The chatbot operates through this automated workflow:

Telegram Trigger

Listens to incoming user messages

Passes data into AI Agent

AI Agent Node

Contains system prompt and conversation rules

Handles greetings, topic selection, session flow

Google Gemini Chat Model

Generates accurate AI responses

Handles explanations for Python, EDA, ML, and DL

Simple Memory Node

Stores selected topic

Maintains session context

Telegram SendMessage Node

Sends final AI response back to student

🔧 Tech Stack / Nodes Used
Component / Node	Description
n8n Automation Platform	Main workflow engine
Telegram Trigger	Receives messages
AI Agent Node	Core chatbot logic (system prompt + flow)
Google Gemini Chat Model	LLM response generator
Simple Memory	Stores conversation state
Telegram SendMessage	Sends chatbot replies
🎯 Use Cases

🎓 AI Mentor for students

❓ Instant doubt-solving assistant

🤖 EdTech chatbot automation

📚 FAQ or learning support bot

💬 Conversational AI without coding
