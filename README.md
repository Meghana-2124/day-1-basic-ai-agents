
# 🤖 Day-1: Basic AI Agents

Conversational AI agent with CLI and web UI built using LangChain and Ollama, featuring memory and prompt templates.

---

## 🧠 Basic AI Chatbot with Memory

This project demonstrates a conversational AI agent built using **LangChain**, **Ollama (Mistral model)**, and **Streamlit**. The chatbot can carry context-aware conversations by utilizing memory, and offers both command-line and web-based interfaces.

---

## ✅ Features

- Context-aware chatbot using **LangChain's memory** module
- Integration with **Mistral model** via **Ollama**
- Prompt engineering with `PromptTemplate` to simulate human-like interaction
- Interactive **Streamlit web UI** with emoji-enhanced chat
- Minimalist **CLI version** for local testing

---

## 🛠️ Tech Stack

- Python 3.9+
- LangChain (`PromptTemplate`, `ChatMessageHistory`)
- Ollama with Mistral model
- Streamlit (for web interface)

---

## 🚀 How to Run

Follow these steps to set up and launch the chatbot:

### 1. Clone the repository

```bash
git clone https://github.com/your-username/day1-basic-ai-agent.git
cd day1-basic-ai-agent
```

### 2. Install dependencies

```bash
pip install streamlit langchain langchain-core langchain-community langchain-ollama
```

### 3. Set up and run Ollama (Mistral model)

Install Ollama from: [https://ollama.com](https://ollama.com)

Then start the Mistral model:

```bash
ollama run mistral
```

> 📝 Keep this terminal open — it powers the AI model.

### 4. Run the Streamlit Web UI

```bash
streamlit run streamlit_version.py
```

Open your browser at [http://localhost:8501](http://localhost:8501) to start chatting.

### 5. Run the CLI version

```bash
python cli_with_memory.py
```

Or try the basic version without memory:

```bash
python basic_ai_agent.py
```
