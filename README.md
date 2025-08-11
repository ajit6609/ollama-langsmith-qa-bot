# 🤖 Ollama + LangSmith Q&A Bot

An AI-powered chatbot built with **Ollama's Gemma:2B model**, integrated with **LangSmith** for advanced conversation tracking, and deployed via **Streamlit** for an interactive UI.  
Perfect for answering questions, experimenting with local LLMs, and tracking performance in real time.

---

## ✨ Features

- 🔍 **Local LLM** — Uses `gemma:2b` from Ollama (fast & private inference)
- 📊 **LangSmith Tracing** — Every conversation is tracked and visualized
- 🎨 **Streamlit Interface** — Clean, minimal, and interactive chat UI
- 🔒 **.env for Secrets** — Keeps API keys safe & out of GitHub
- 🛠 **Customizable Prompt Pipeline** — Built with LangChain for easy tweaking

---

## 📸 Demo Screenshots

<img width="1211" height="601" alt="image" src="https://github.com/user-attachments/assets/a9f3f3b7-c826-4007-afdf-9128e2a69c3f" />


---

## 🚀 Getting Started

### 1️⃣ Install Dependencies
pip install -r requirements.txt

### 2️⃣ Setup .env
Create a .env file in the project root:
LANGCHAIN_API_KEY=ls__your_langsmith_api_key
LANGCHAIN_PROJECT=ollama-langsmith-bot

### 3️⃣ Run Ollama
Make sure Ollama is installed and the gemma:2b model is pulled:
ollama run gemma:2b

### 4️⃣ Start Streamlit App
streamlit run app.py

# Created with ❤️ by Ajit
