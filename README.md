# German-AI-Receptionist
An AI-powered voice receptionist designed to handle customer calls, manage conversations in German, and book appointments automatically. Built for real-world business workflows, not just demos.

## 🚀 What it does

This project demonstrates how AI can be used to automate inbound/outbound calls, interact naturally with customers, and perform actions like scheduling appointments and updating records in real time.
The system is optimized for German conversations, including formal communication (“Sie”), accurate handling of dates and numbers, and a professional tone.

## 🧠 Key Features
- 📞 Automated outbound call handling
- 🗣️ Natural voice conversations (German-optimized)
- 📅 Real-time appointment booking
- 🔄 CRM integration for live data updates
- ⚙️ Backend-driven workflow orchestration
- 🚀 Designed for production use cases


## 🧠 How It Works
- A new lead is received (via webhook or form)
- Backend system processes the request
- AI initiates a call to the customer
- Real-time conversation happens (STT → LLM → TTS)
- System performs actions (check slots, book appointment)
- CRM is updated instantly


## 🛠️ Tech Stack

<img width="1641" height="958" alt="AI_German_Receptionist" src="https://github.com/user-attachments/assets/fa77ef5a-35ed-4fbf-9a17-86258a960cbd" />



- Backend: Python, FastAPI
- Voice AI Platform: Vapi
- LLM: GPT-4o
- Speech-to-Text: Optimized for German
- Text-to-Speech: Natural voice output
- Data Layer: Mock CRM

## 🎥 Demo
[Click here for demo](https://youtube.com/shorts/uxl4FK3CSlw?feature=share)


## 💡 Why this matters
It reduces manual work, responds to leads instantly, and ensures you never miss a booking.


