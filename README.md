# 🤖 Agentic AI Email Notification System

✨ A real-world Agentic AI workflow that **thinks, decides, and acts** using LLM reasoning and Gmail automation.

---

## 🚀 Overview

This project showcases a **practical Agentic AI system** built using **n8n**, **OpenAI (ChatGPT)**, and **Gmail**.

Instead of a simple chatbot, the system behaves like an **AI agent**:
- It receives context
- Reasons using an LLM
- Takes action in the real world by sending emails

The goal of this project is to understand and demonstrate **Agentic AI fundamentals** through a working automation.

---

## 🧠 What Makes This Agentic AI?

This workflow follows the **Agent Loop**:

**Input → Reasoning → Action**

| Agent Component | Implementation |
|-----------------|----------------|
| Input | Manual Trigger + Set Node |
| Reasoning | OpenAI (LLM-based message generation) |
| Decision | AI-crafted notification content |
| Action | Gmail → Send Email |
| Autonomy | No manual message writing |

This design reflects how modern AI agents operate in production systems.

---

## 🏗️ Workflow Architecture

Manual Trigger
↓
Set (Input Message)
↓
OpenAI (AI Reasoning)
↓
Gmail (Send Email)

<img width="1566" height="671" alt="workflow-canvas png" src="https://github.com/user-attachments/assets/17b4f780-ad68-452c-8558-8f1604488326" />

---
## ⚙️ How the Workflow Works

### 🔹 Manual Trigger
Allows controlled execution for testing, demos, and learning.

### 🔹 Set Node
Provides the message or context that the AI agent will process.

### 🔹 OpenAI Node
Uses a Large Language Model to:
- Understand the input
- Rewrite it into a clear, human-friendly notification
- Prepare it for real-world delivery

### 🔹 Gmail Node
Sends the AI-generated message as a **real email**, proving end-to-end functionality.

---

## 🛠️ Tech Stack

- **n8n** – Workflow automation & orchestration  
- **OpenAI (ChatGPT)** – LLM-based reasoning  
- **Gmail API** – Real email delivery  
- **Agentic AI Design Pattern**

---

## 📸 Screenshots & Demo

Screenshots included in the `screenshots/` folder:
- n8n workflow canvas
- Email received in Gmail inbox

These demonstrate the agent working in real conditions.

---


---

## 🎯 Use Cases

- AI-powered notification systems  
- Intelligent email assistants  
- AI + automation learning projects  

---

## 🔮 Future Improvements

- Incoming email summarization
- Urgency detection & classification
- Auto-triggered workflows (webhooks/events)
- Multi-agent architecture (planner + executor)
- Integration with Slack, WhatsApp, or DevOps alerts

---

## 👨‍💻 Author

**Kushwanth Chowdary**  
Computer Science Student | AI & Automation Enthusiast

---

⭐ IF this project helped you understand Agentic AI, feel free to star the repository!

