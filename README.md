# RAG Chatbot using LangChain, OpenAI, Google AI & Hugging Face

<div align="center">
  <img src="https://github.com/bijarnialokesh/RAG-CHATBOT-WITH-LANGCHAIN/blob/main/data/docs/RAG_architecture.png">
  <figcaption>RAG architecture with LangChain components.</figcaption>
</div>

## 📌 Project Overview

Large Language Models (LLMs) are powerful, but they rely on static training data.  
This means they can produce **outdated or incorrect answers**.

To solve this, we use **Retrieval Augmented Generation (RAG)**.

This project builds a **RAG-powered chatbot** using:

- LangChain  
- OpenAI  
- Google Generative AI  
- Hugging Face  

You can upload documents in the following formats:

- `.txt`
- `.pdf`
- `.csv`
- `.docx`

Then you can **chat with your own data**.  
The system retrieves the most relevant parts of your documents and sends them to the AI model to generate **accurate, context-aware answers**.

A simple **Streamlit web app** is used as the user interface.

---

## 🧱 How It Works

1. Load documents  
2. Split them into chunks  
3. Convert them into embeddings  
4. Store them in a Chroma vector database  
5. Retrieve relevant content for each query  
6. Send it to the LLM for precise answers  

---

## ⚙️ Requirements

- Python 3.x  
- Required libraries:
