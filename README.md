# 🤖 AI News Multi-Agent

An AI-powered multi-agent system that researches the latest AI news,
summarizes it in English and Arabic, and delivers the results through
Email and Telegram.

## 🏗️ Architecture

User / Scheduled Trigger
        ↓
        
Researcher Agent
        ↓
        
Tavily Web Search
        ↓
        
AI News Research & Summarization
        ↓
        
Sender Agent

      ↙   ↘
Telegram  Gmail

## 🚀 Features

- 🔎 Searches for recent AI news
- 🧠 Researcher Agent for news collection and summarization
- 📧 Sends English summaries via Email
- 📱 Sends Arabic summaries via Telegram
- 🌐 Uses Tavily for web search
- 🔗 Built with LangChain Agents
- 🤖 Uses an LLM through OpenRouter

## 🛠️ Tech Stack

- Python
- LangChain
- OpenRouter
- Tavily
- Telegram Bot API
- Gmail SMTP
- Jupyter / Kaggle

## 📌 Current Status

This project currently implements the core multi-agent workflow.

### Completed
- Researcher Agent
- Web search
- News summarization
- Arabic/English formatting
- Telegram delivery
- Email delivery


## 🔐 Security

API keys and credentials are stored using environment variables /
Kaggle Secrets and are not included in the repository.
