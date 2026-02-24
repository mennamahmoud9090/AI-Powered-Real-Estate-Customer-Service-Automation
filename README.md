# 🏠 AI-Powered Real Estate Customer Service Agent

An intelligent automated assistant designed for real estate agencies. This project uses **n8n** to provide instant, AI-driven support for property inquiries and lead management via **Telegram**.

---

## 🚀 Overview
This system acts as a 24/7 virtual real estate agent. It communicates with customers in natural language, answers questions about listings, and organizes potential leads for the sales team.

---

## 🛠 Tech Stack
* **Automation Platform:** n8n
* **Generative AI:** Google Gemini AI (LLM)
* **Messaging Interface:** Telegram Bot API
* **Lead Tracking:** Google Sheets
* **Data Logging:** MySQL

---

## ⚙️ How It Works
* **Customer Interaction:** The process starts when a user sends a message to the Telegram bot.
* **AI Processing:** The AI Agent (Gemini) analyzes the inquiry and generates a personalized response based on property data.
* **Conversation Memory:** The agent remembers previous messages in the chat to provide a smooth, human-like conversation.
* **Automatic Capture:** Key details (like customer name and requirements) are instantly saved to a Google Sheet.
* **Log Management:** All interactions are stored in a MySQL database for record-keeping and future analysis.

---

## 📦 How to Use
1. **Import the Workflow:** Download the provided `.json` file and upload it to your n8n workspace.
2. **Setup Credentials:** Connect your own API keys for Telegram, Google Gemini, and Google Sheets.
3. **Activate:** Once the credentials are set, the bot is ready to handle real-time inquiries.

---

## 📸 Workflow Preview
*(Upload your screenshot here to display the workflow visualization)*
![Workflow Screenshot](<img width="1919" height="1026" alt="Screenshot 2026-02-22 165635" src="https://github.com/user-attachments/assets/f4a0c9c7-5d20-4ed4-9cfc-d4fedd6b92fd" />
)

---
