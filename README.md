# 🧭 Intern Onboarding Guide: RAG-based Knowledgebase Project (Backend Only)

## 📌 Project Overview
You’ll be working on a Retrieval-Augmented Generation (RAG) system with:
- A persistent knowledge base.
- PDF upload functionality for user-generated content.
- FastAPI-based backend serving the AI logic and endpoints.
- A UI (handled separately).

---

## 🔁 Learning Roadmap (in Order of Usage)

### 1. 🔧 **Git & GitHub Basics**
**Goal**: Understand version control and collaboration.

- [Git Handbook by GitHub](https://guides.github.com/introduction/git-handbook/)
- [Codecademy: Learn Git (Free)](https://www.codecademy.com/learn/learn-git)
- [Oh My Git! Game (for fun)](https://ohmygit.org/)

---

### 2. 🧱 **Python OOP Fundamentals**
**Goal**: Write modular, scalable code using classes and objects.

- [Python OOP – Real Python](https://realpython.com/python3-object-oriented-programming/)
- [OOP in Python - Programiz](https://www.programiz.com/python-programming/object-oriented-programming)
- [CS50’s Python Notes on OOP (short & clear)](https://cs50.harvard.edu/python/2022/notes/8/)

---

### 3. ⚙️ **FastAPI**
**Goal**: Build scalable backend APIs.

- [FastAPI Official Docs (start with the tutorial)](https://fastapi.tiangolo.com/tutorial/)
- [FastAPI Crash Course – freeCodeCamp (YouTube)](https://www.youtube.com/watch?v=0sOvCWFmrtA)
- [FastAPI + SQLite example repo](https://github.com/tiangolo/full-stack-fastapi-postgresql)

---

### 4. 🧠 **AI Basics for RAG**
**Goal**: Understand LLMs, embeddings, tokenization, vector search.

- [Intro to LLMs (Cohere Learn)](https://learn.cohere.com/)
- [OpenAI Cookbook – Embeddings, Token Usage](https://github.com/openai/openai-cookbook)
- [Hugging Face Course (relevant parts)](https://huggingface.co/learn/nlp-course/chapter1)

---

### 5. 📥 **PDF Parsing & Text Extraction**
**Goal**: Process user-uploaded PDFs for embedding into vector DB.

- [pdfplumber (GitHub)](https://github.com/jsvine/pdfplumber)
- [PyMuPDF (fitz) – Accurate & Fast](https://pymupdf.readthedocs.io/en/latest/)

---

### 6. 🗃️ **Vector Databases**
**Goal**: Store and retrieve embeddings for documents.

- [Introduction to Vector DBs (Pinecone Blog)](https://www.pinecone.io/learn/vector-database/)
- [Chroma DB – Lightweight local DB](https://docs.trychroma.com/)
- [FAISS – Facebook AI Similarity Search](https://github.com/facebookresearch/faiss)

---

### 7. 🧠🔗 **RAG Architecture**
**Goal**: Understand how retrieval + generation work together.

- [RAG from First Principles – Sebastian Raschka](https://sebastianraschka.com/blog/2023/rag.html)
- [LangChain Docs – RAG Concept](https://docs.langchain.com/docs/use-cases/question-answering/)
- [LangChain RAG YouTube Tutorial (Data Independent)](https://www.youtube.com/watch?v=YIu5kZpLkJQ)

---

### 8. 🧪 **Testing and Debugging**
**Goal**: Ensure reliability and stability of your APIs and modules.

- [Pytest Quickstart – Real Python](https://realpython.com/pytest-python-testing/)
- [FastAPI Testing Docs](https://fastapi.tiangolo.com/tutorial/testing/)

---

### 9. 🗃️ **Database for Metadata**
**Goal**: Store metadata like file info, user info, query logs, etc.

- [SQLModel (by FastAPI creator)](https://sqlmodel.tiangolo.com/)
- [SQLite Crash Course (YouTube)](https://www.youtube.com/watch?v=byHcYRpMgI4)

---

### 10. 📦 **Packaging & Deployment Basics**
**Goal**: Make your app production-ready.

- [Deploy FastAPI with Uvicorn & Gunicorn](https://fastapi.tiangolo.com/deployment/)
- [Dockerize FastAPI – FreeCodeCamp](https://www.youtube.com/watch?v=YpTmcCBBdTE)

---

## ✅ Expected Setup & Tools
- Python 3.10+
- VS Code or PyCharm
- Git + GitHub
- FastAPI
- SQLite or PostgreSQL
- ChromaDB / FAISS
- OpenAI / Hugging Face models
- Docker (optional but recommended for later stages)
