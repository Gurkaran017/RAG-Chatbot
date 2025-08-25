# 💬 RAG Chatbot with Streamlit + LangChain + Google Gemini

A **Retrieval-Augmented Generation (RAG) chatbot** built with **Streamlit**, **LangChain**, and the **Google Gemini API**.  
This chatbot lets you **upload and query your PDF knowledge base**, retrieving **context-aware answers** in a smooth chat-like interface.

---

## 🚀 Features

- 📄 **PDF Knowledge Base** → Chat directly with your documents  
- 🔍 **Smart Retrieval** → Uses **Chroma DB** for persistent vector storage  
- 🧠 **AI-Powered Responses** → Powered by **Google Gemini LLM**  
- 🧩 **Semantic Chunking** → Uses `SemanticChunker` for meaningful document splitting  
- 💬 **Real-time Chat** → User messages on the right, bot responses on the left  
- ⏳ **Streaming Mode** → Word-by-word typing effect for a natural chatbot feel  
- 📊 **Live Statistics** → Track total messages & questions in sidebar  
- 🗑️ **Clear Chat** → Reset conversation anytime  

---

## 📂 Project Structure

**rag-chatbot/**  
**│── main.py** – Streamlit UI and chatbot logic  
**│── vector_store.py** – Creates/loads Chroma vector DB  
**│── splitter.py** – Splits PDFs into semantic chunks  
**│── loader.py** – Loads PDF documents  
**│── config.py** – API keys, model setup, DB paths  
**│── AppleData-2024.pdf** – Sample knowledge base PDF  
**│── requirements.txt** – Python dependencies  
**│── README.md** – Project documentation  
**│── .env** – Store Google API key here  


---

## 🛠️ Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/rag-chatbot.git
   cd rag-chatbot
