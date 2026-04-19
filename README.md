# 🧠 GenAI Real-Time News Assistant

A production-style **GenAI application** that delivers real-time news using **LLMs + external APIs + vector memory (RAG)**.

---

## 🚀 Overview

This project combines:

* ⚡ Fast LLM inference using Groq
* 🌐 Real-time data via News API
* 🧠 Memory using FAISS (Vector Database)
* 🔗 Orchestration with LangChain

👉 Ensures accurate, up-to-date, and context-aware responses.

---

## 🏗️ Architecture

```
User Query
   ↓
Style Detection (bullets / summary / detailed)
   ↓
FAISS Retriever (Past Memory)
   ↓
News API (Real-Time Data)
   ↓
Prompt Builder
   ↓
Groq LLM
   ↓
Response Generation
   ↓
Store in FAISS (Memory)
```

---

## ⚙️ Tech Stack

* Python
* LangChain
* Groq API
* FAISS (Vector Store)
* NewsAPI
* Sentence Transformers

---

## 🔥 Features

* ✅ Real-time news retrieval
* ✅ Multi-style responses (bullets, summary, detailed)
* ✅ RAG-based memory (FAISS)
* ✅ Prompt engineering for structured output
* ✅ Tool-based architecture (prevents hallucination)

---

## ▶️ How to Run

```bash
git clone https://github.com/your-username/GenAI-News-Assistant.git
cd GenAI-News-Assistant

pip install -r requirements.txt
```

Create `.env` file:

```
GROQ_API_KEY=your_key
NEWS_API_KEY=your_key
```

Run:

```bash
python app.py
```

---

## 💬 Example

**User:** latest AI news

**Bot:**

* OpenAI released new updates
* Google introduced AI features
* AI startups raised funding
* Governments discussing regulations
* AI adoption increasing globally

---

## 🧠 Key Concepts Used

* Retrieval-Augmented Generation (RAG)
* Vector Search using FAISS
* Prompt Engineering
* Tool Calling with LangChain

---

## ⚠️ Limitations

* Depends on News API availability
* Slight delay in real-time updates
* Free-tier API limits

---

## 🚀 Future Improvements

* Streamlit UI (chat interface)
* Multi-agent architecture
* Deployment (AWS / Docker)
* Advanced query rewriting
* Hybrid search (news + documents)

---

## 👨‍💻 Author

Sabari R
