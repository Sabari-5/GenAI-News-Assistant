# 🧠 GenAI Real-Time News Assistant

An intelligent **GenAI-powered chatbot** that delivers **real-time news** using LLMs, APIs, and vector memory (RAG).

---

## 🚀 Features

* 🌐 Real-time news retrieval (News API)
* ⚡ Fast responses using Groq LLM
* 🧠 Memory with FAISS (RAG)
* 🎯 Multi-style output (bullets, summary, detailed)
* 🔗 LangChain-based orchestration
* ❌ Prevents hallucination using live data

---

## 🏗️ Architecture

```mermaid
flowchart TD
    A[User Query] --> B[Style Detection]
    B --> C[FAISS Memory]
    C --> D[News API]
    D --> E[Prompt Builder]
    E --> F[Groq LLM]
    F --> G[Final Response]
    G --> H[Store in FAISS]
```

---

## ⚙️ Tech Stack

* Python
* LangChain
* Groq API
* FAISS (Vector DB)
* NewsAPI
* Sentence Transformers

---

## ▶️ How to Run

```bash
git clone https://github.com/Sabari-5/GenAI-News-Assistant.git
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

## 💬 Example Output

**User:** latest AI news

**Bot:**

Bot: - **Allbirds rebrands as an AI company** – The shoe maker announced it is now an AI firm, causing its stock price to surge dramatically, highlighting the “AI is inevitable” hype cycle.  
- **Samsung’s 2026 TV lineup** – Samsung introduced the Frame Pro and new OLED models, emphasizing artistic design while integrating advanced AI-driven features for picture and content recommendation.  
- **Dairy Queen adds AI chatbots to drive‑thrus** – The fast‑food chain is deploying AI‑powered chat assistants in dozens of U.S. and Canadian locations to speed service and encourage larger orders.  
- **Cultural backlash against AI** – A growing public backlash is emerging as companies rush to adopt AI, with many people expressing distrust and fatigue over constant AI hype.  
- **Meta layoffs to fund AI expansion** – Meta is cutting hundreds of jobs across recruiting, social media, sales, and its Reality Labs division as it redirects resources toward further AI development.

---

## 🧠 Key Concepts

* Retrieval-Augmented Generation (RAG)
* Vector Search (FAISS)
* Prompt Engineering
* Tool-based AI system

---

## ⚠️ Limitations

* Depends on API availability
* Slight delay in real-time data
* Free API rate limits

---

## 🚀 Future Improvements

* Streamlit UI
* Multi-agent architecture
* Deployment (AWS / Docker)
* Advanced query rewriting

---
## 💡 Highlights
- Built a real-time GenAI system combining APIs + LLM + vector memory
- Implemented RAG to improve response accuracy
- Designed prompt engineering for structured outputs

---
## 👨‍💻 Author

**Sabari R**
