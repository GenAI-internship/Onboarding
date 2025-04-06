# 🧭 Intern Onboarding Guide: RAG-based Knowledgebase Project (Backend Only)

## 📌 Project Overview
You’ll be working on a Retrieval-Augmented Generation (RAG) system with:
- A persistent knowledge base.
- PDF upload functionality for user-generated content.
- FastAPI-based backend serving the AI logic and endpoints.
- A UI (handled separately).

---

# **Onboarding Plan: 2-Week Intensive Learning → 6-Week Implementation**  

This plan **front-loads learning** in the first two weeks, ensuring interns can **start integration early**.  

---  

## **📌 Phase 1: Intensive Learning (Weeks 1-2)**  
**Goal:** Cover all fundamentals needed to **start building immediately** in Week 3.  

### **Week 1: Core Backend & AI Basics**  
| **Day** | **Topic** | **Resources** | **Checkpoint Task** |  
|---------|----------|--------------|---------------------|  
| **1** | Python OOP Refresher | [FreeCodeCamp OOP](https://youtu.be/Ej_02ICOIgs) | Write a Python class for a "Document" (title, content, metadata) |  
| **2** | Git & Collaboration | [Learn Git Branching](https://learngitbranching.js.org/) | Fork repo, make a PR with a small change |  
| **3** | FastAPI Basics | [FastAPI Tutorial](https://fastapi.tiangolo.com/tutorial/) | Build a `/health` endpoint |  
| **4** | FastAPI File Uploads | [FastAPI Upload Files](https://fastapi.tiangolo.com/tutorial/request-files/) | Make an endpoint that accepts PDFs |  
| **5** | NLP Crash Course | [Hugging Face NLP](https://huggingface.co/course/chapter1) | Extract keywords from a sample text |  

### **Week 2: RAG Prerequisites**  
| **Day** | **Topic** | **Resources** | **Checkpoint Task** |  
|---------|----------|--------------|---------------------|  
| **6** | Vector Databases | [Pinecone Guide](https://www.pinecone.io/learn/vector-database/) | Store 3 text chunks in FAISS |  
| **7** | LangChain Basics | [LangChain Docs](https://python.langchain.com/docs/get_started) | Load a PDF and split into chunks |  
| **8** | LangChain RAG | [RAG Tutorial](https://python.langchain.com/docs/use_cases/question_answering/) | Build Q&A over a PDF |  
| **9** | LangGraph (Optional) | [LangGraph Docs](https://python.langchain.com/docs/langgraph) | Chain two LLM calls (e.g., summarize → answer) |  
| **10** | Project Planning | — | Draft a system design doc |  

---  

## **📌 Phase 2: Implementation (Weeks 3-8)**  
**Goal:** Build the RAG system incrementally with **weekly milestones**.  

### **Week 3: Setup & PDF Processing**  
- **Objective:** Accept PDFs → Extract text → Store in DB.  
- **Tasks:**  
  - FastAPI endpoint for PDF upload.  
  - Text extraction with PyPDF2/PDFMiner.  
  - Store raw text in SQLite/PostgreSQL.  

### **Week 4: Vector DB & Embeddings**  
- **Objective:** Chunk text → Generate embeddings → Store in FAISS/Pinecone.  
- **Tasks:**  
  - Implement text splitting (LangChain `RecursiveTextSplitter`).  
  - Generate embeddings (OpenAI, Hugging Face, or local model).  
  - Set up vector DB.  

### **Week 5: RAG Pipeline**  
- **Objective:** User query → Retrieve chunks → Generate answer.  
- **Tasks:**  
  - Implement retrieval with LangChain.  
  - Connect to LLM (OpenAI, Llama 2, etc.).  
  - Simple `/query` endpoint.  

### **Week 6: Workflow & Optimization**  
- **Objective:** Improve RAG with LangGraph (if needed).  
- **Tasks:**  
  - Add query rewriting (e.g., "Explain like I'm 5").  
  - Cache frequent queries with Redis.  

### **Week 7: Testing & Edge Cases**  
- **Objective:** Handle errors (scanned PDFs, large files, etc.).  
- **Tasks:**  
  - Add OCR (Tesseract) for scanned PDFs.  
  - Rate limiting + file size checks.  

### **Week 8: Deployment & Docs**  
- **Objective:** Dockerize + deploy + document.  
- **Tasks:**  
  - Docker + FastAPI (Uvicorn).  
  - Write API docs (Swagger/Postman).  
  - Present final demo.  

---  

## **📌 Key Principles**  
1. **First 2 Weeks = Full-Time Learning**  
   - Daily check-ins to resolve blockers.  
   - Focus on **applied tasks** (not just theory).  

2. **Weeks 3+ = Build in Sprints**  
   - Weekly milestones (e.g., "By Friday, PDF upload works").  
   - Prioritize **end-to-end flow** over perfection.  

3. **Stretch Goals**  
   - Auth (JWT), monitoring (Prometheus), async processing (Celery).  

---  

### **🚀 Expected Outcomes**  
- By **Week 3**: Working PDF upload API.  
- By **Week 5**: Basic RAG (upload → query).  
- By **Week 8**: Production-ready system.  

Let’s ship this!  

---  
**Mentor:** Sankalp Jain 
**Start Date:** 07/04/2025 
**Demo Day:** TBD
