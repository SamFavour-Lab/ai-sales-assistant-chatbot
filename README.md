# 🤖 AI Sales Assistant Chatbot

An intelligent AI-powered sales assistant built with **n8n** that engages customers in real-time conversations, qualifies leads, stores interaction history, and schedules appointments using Google Calendar — all powered by an AI Agent with memory and tools.

---

## 📌 Overview

Businesses often lose potential customers because they cannot respond instantly or handle multiple conversations at once.

This AI Sales Assistant solves that problem by acting as a 24/7 digital sales representative that can chat with customers, answer questions, collect information, and book appointments automatically.

---

## 🚀 Business Problem

Sales teams face challenges such as:

- Missed leads due to slow response time
- Limited availability outside working hours
- Manual lead qualification
- Inconsistent customer engagement
- Difficulty managing multiple conversations

---

## ✅ Solution

This workflow automatically:

1. Receives incoming chat messages from customers.
2. Processes messages using a Groq AI Agent.
3. Maintains conversation memory for context-aware responses.
4. Logs conversations into Google Sheets.
5. Uses a code tool for custom logic when needed.
6. Schedules appointments using Google Calendar.

---

## 🛠 Technologies Used

- n8n
- Chat Trigger
- Groq Chat Model
- AI Agent
- Simple Memory
- Google Sheets
- Google Calendar
- Code Tool

---

## 🔄 Workflow Overview

```text
Chat Message Received
          │
          ▼
AI Agent (Groq LLM)
          │
          ├── Memory (Context Tracking)
          ├── Google Sheets (Logging)
          ├── Code Tool (Logic Processing)
          └── Google Calendar (Scheduling)
          │
          ▼
AI Response Sent to User
```

---

## 📷 Workflow Screenshot

![Workflow Overview](assets/screenshots/workflow-overview.png)

---

## 💼 Business Value

- Provides 24/7 automated sales support
- Increases lead conversion rates
- Reduces workload for sales teams
- Improves customer engagement
- Automates appointment scheduling
- Captures and stores all customer interactions

---

## ✨ Key Features

- AI-powered conversational assistant
- Memory-based contextual responses
- Lead qualification automation
- Google Calendar integration
- Real-time conversation logging
- Scalable sales automation system

---

## 🎯 Skills Demonstrated

- AI Agent Development
- Sales Automation
- Conversational AI
- Workflow Automation
- Prompt Engineering
- Memory-based AI systems
- Google Calendar Integration
- Google Sheets Integration
- n8n Development

---

## 📂 Repository Structure

```text
.
├── assets
│   ├── docs
│   └── screenshots
│       └── workflow-overview.png
├── workflow.json
└── README.md
```

---

## 🚀 Future Improvements

- WhatsApp integration
- Voice-based conversations
- CRM synchronization
- AI sales analytics dashboard
- Multi-language support
- Advanced lead scoring system

---

## 👨‍💻 Author

**Samuel Favour**

AI Automation Specialist

GitHub: https://github.com/SamFavour-Lab

---

### ⭐ If you found this project helpful, consider giving the repository a star.
