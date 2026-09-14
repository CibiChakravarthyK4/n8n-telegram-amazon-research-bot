# n8n-telegram-amazon-research-bot

# 🛒 Telegram Amazon Research Agent

An intelligent n8n AI agent that brings live Amazon product research directly to your Telegram chat.

[ Telegram Trigger ] ──► [ Research Agent ] ──► [ Telegram Response ]
│
┌──────────────────┼──────────────────┐
▼                  ▼                  ▼
[ OpenAI Model ]   [ Simple Memory ]  [ Amazon SerpApi ]

## ⚡ Quick Architecture

## ✨ Features

* **Instant Product Lookup:** Search for items, compare prices, and check details on Amazon using natural language.
* **Conversational Memory:** Retains chat context so you can ask follow-up questions seamlessly.
* **Live Web Data:** Powered by SerpApi's Amazon integration for real-time results.

## 🛠️ Prerequisites & Setup

1. **n8n Instance:** Self-hosted or cloud-based n8n environment.
2. **Credentials Needed:**
   * **Telegram Bot Token** (from [@BotFather](https://t.me/BotFather))
   * **OpenAI API Key**
   * **SerpApi API Key**

## 🚀 Installation

1. Import the workflow JSON file into your n8n dashboard.
2. Link your **Telegram**, **OpenAI**, and **SerpApi** credentials to their respective nodes.
3. Toggle the workflow to **Active**.
4. Start chatting with your Telegram bot to test product searches!


with open("README_Research_Agent.md", "w", encoding="utf-8") as f:
    f.write(readme_content)
