# 🎬 Netflix Tamil Thriller Telegram Bot

An AI-powered Telegram bot that helps users discover Tamil thriller movies available on Netflix — built with **n8n**, **OpenAI**, and the **Streaming Availability API**.

## ✨ Features
- Conversational AI Agent (like ChatGPT) — understands natural language questions
- Searches real-time Netflix availability for Tamil thriller movies
- Remembers conversation context (e.g., "what was the 5th movie?")
- Fully automated via Telegram — no app installation needed for users

## 🛠️ Tech Stack
- **n8n** — no-code workflow automation (self-hosted)
- **Telegram Bot API** — trigger & reply
- **OpenAI GPT-4o-mini** — conversational AI Agent
- **RapidAPI Streaming Availability API** — live Netflix movie data

## ⚙️ How It Works
1. User sends a message to the Telegram bot
2. n8n's **AI Agent** node processes the request using OpenAI
3. The agent calls the **Streaming Availability API** (as a Tool) to fetch real Tamil thriller movies on Netflix (India)
4. A **Memory** node keeps conversation context for follow-up questions
5. The AI's response is sent back to the user via Telegram

## 📂 Setup
1. Import `My workflow.json` into your n8n instance
2. Add credentials:
   - Telegram Bot Token (via [@BotFather](https://t.me/BotFather))
   - OpenAI API Key
   - RapidAPI Key (Streaming Availability API)
3. Activate the workflow
4. Start chatting with your bot on Telegram!

## 👤 Author
Built by [swarnasudarshan3-prog](https://github.com/swarnasudarshan3-prog) using n8n + AI automation.
