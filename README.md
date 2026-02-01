# agentic-ai-rag-chatbot
A LangGraph-powered RAG chatbot that answers questions strictly from the Agentic AI eBook using semantic search, Pinecone vector storage, and grounded LLM responses, exposed via a FastAPI interface.
# Agentic AI RAG Chatbot (LangGraph + Pinecone)

This project implements a **Retrieval-Augmented Generation (RAG)** based AI chatbot
that answers questions **strictly grounded** in the *Agentic AI eBook*.

The system uses **LangGraph** for orchestration, **Pinecone** as the vector database,
and **text embeddings** for semantic retrieval.

---

## 🚀 Features
- PDF ingestion and intelligent chunking
- Vector-based semantic search
- LangGraph-powered RAG pipeline
- Strict hallucination control
- API-based chatbot using FastAPI
- Retrieved context + confidence score in responses

---

## 🧱 Tech Stack
- Python 3.10+
- LangChain (0.1+)
- LangGraph
- Pinecone
- OpenAI Embeddings & Chat Models
- FastAPI
