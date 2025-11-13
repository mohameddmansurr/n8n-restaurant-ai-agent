# 🍽️ Restaurant CS AI Agent (n8n Workflows)

This repository contains **two n8n workflows** that together form an intelligent Restaurant Customer Service (CS) AI system powered by **Retrieval-Augmented Generation (RAG)**.

## 📂 Project Structure

n8n-restaurant-ai-agent/
├── workflows/
│ ├── Restaurant CS AI Agent.json # Main AI agent workflow
│ └── Restaurant Info.json # RAG data and restaurant info
└── README.md

---

## 🤖 Overview

### 1. Restaurant CS AI Agent
This workflow acts as the **main AI agent** that interacts with customers.
- Handles chat input and responses
- Uses context from the "Restaurant Info" RAG workflow
- Connects to AI nodes (e.g., OpenAI, HuggingFace, or local models)
- Automates customer queries, reservations, and feedback

### 2. Restaurant Info (RAG)
This workflow provides **structured restaurant data** for retrieval.
- Contains menu details, service info, and restaurant metadata
- Powers the AI agent with up-to-date information

---

## ⚙️ How to Import into n8n

1. Open **n8n**
2. Click **Workflows → Import from File**
3. Upload both `.json` files from the `workflows` folder
4. Check that both workflows are active and connected

---

## 🧠 Recommended Use

You can integrate these with:
- **OpenAI API** (for GPT responses)
- **PostgreSQL / Notion / Google Sheets** (for menu or booking data)
- **Telegram / WhatsApp / Webhooks** (for chatbot deployment)

---

## 📜 License
MIT License © 2025 Mohamed Ali Mansour
