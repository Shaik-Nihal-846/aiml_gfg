# Day 18
## 💬 RAG Chatbot — Chat with Your Knowledge Base

This project builds a **Retrieval-Augmented Generation (RAG) chatbot** that answers questions using custom documents rather than internet-based LLM memory.

### 🎯 Objective
Create a chatbot that provides reliable, document-grounded responses using embeddings + vector search.

### 📌 Workflow
1. Ingest and chunk PDFs / text files.
2. Generate embeddings using sentence-transformer model.
3. Store vectors in a database (FAISS / Pinecone).
4. Retrieve top-k relevant chunks based on query similarity.
5. Feed retrieved context to an LLM to generate responses.

### 🔍 Key Insights
- RAG prevents hallucinations by grounding answers in documents.
- Chunk size + embedding model choice heavily influence accuracy.
