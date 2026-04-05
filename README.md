# 🧠 RAG Architectures Hub: From Local to Cloud-Native

Welcome to the **RAG Architectures Hub**. This repository serves as a technical comparison of three distinct ways to build Retrieval-Augmented Generation (RAG) systems, ranging from 100% private local setups to fully automated cloud-native pipelines.

---

## 📊 Comparison of Approaches

| Feature | 01. Local RAG | 02. Hybrid RAG | 03. Automated RAG |
| :--- | :--- | :--- | :--- |
| **Model** | Ollama (Llama 3/Mistral) | Groq (Cloud Inference) | Groq (Cloud Inference) |
| **Vector DB** | ChromaDB (Local) | FAISS (In-Memory) | Pinecone (Serverless) |
| **Framework** | LangChain (Python) | LangChain (Notebook) | n8n (Low-Code) |
| **Best For** | Privacy & Offline use | Research & Prototyping | Production & Scalability |

---

## 📁 Project Breakdown

### [01. Local RAG with Ollama & Chroma](./01-local-rag-ollama/)
A fully private implementation. No data leaves your machine. 
* **Key Learnings:** Handling local embeddings, managing vector persistence, and Ollama integration.

### [02. Cloud-Hybrid RAG with Groq & FAISS](./02-hybrid-rag-groq/)
Focuses on speed and rapid prototyping using a Jupyter Notebook environment.
* **Key Learnings:** Leveraging high-speed inference (Groq) and efficient in-memory similarity search with FAISS.

### [03. Automated RAG with n8n & Pinecone](./03-automated-rag-n8n/)
An end-to-end automated pipeline with a custom-built web chat interface.
* **Key Learnings:** API orchestration, serverless vector databases, and frontend-to-backend integration via webhooks.

---

## 🛠️ Global Setup

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/your-username/RAG-Architectures-Hub.git](https://github.com/your-username/RAG-Architectures-Hub.git)