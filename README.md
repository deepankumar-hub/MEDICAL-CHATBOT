# MEDICAL-CHATBOT - Context-Aware Q&A System

A **context-aware medical question-answering chatbot** that retrieves relevant information from a **local medical knowledge base** using **FAISS vector search**, and generates accurate, conversational responses using  **Groq-hosted Large Language Models (LLMs)**.

## Technical Architecture

User Query
↓
Text Embedding (SentenceTransformers)
↓
FAISS Vector Store
↓
Context Retrieval (Top-k relevant chunks)
↓
LLM (HuggingFace / Groq)
↓
Generated Answer

## Technologies Used
## Component	             ## Library / Tool
Embeddings	              SentenceTransformers / OpenAI / InstructorXL
Vector Store	            FAISS
LLM Backend	              HuggingFace / Groq
Framework	                LangChain
Interface	                Streamlit / CLI
Language	                Python 3.10+
