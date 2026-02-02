# Code Documentation Navigator

An AI-powered code understanding tool that uses Retrieval-Augmented Generation (RAG) to help developers quickly navigate, explain, and onboard onto large GitHub repositories.

## 🚀 Problem Statement
Understanding large and unfamiliar codebases is time-consuming and frustrating, especially for new developers. Existing documentation is often outdated, incomplete, or scattered across files.

## 💡 Solution
Code Documentation Navigator allows developers to ask natural-language questions about a codebase and receive accurate, context-aware answers grounded directly in the source code.

## 🧠 How It Works
1. The codebase is ingested and split into meaningful chunks.
2. Code embeddings are generated and stored in a vector database.
3. User queries are matched with relevant code snippets using semantic search.
4. A Large Language Model (LLM) generates clear explanations using retrieved context.

## ✨ Key Features
- Natural language queries over source code
- RAG-based accurate and explainable responses
- Faster onboarding for new developers
- Supports large GitHub repositories
- Reduces dependency on manual documentation

## 🛠️ Tech Stack
- Python
- Large Language Model (LLM)
- Vector Database (FAISS / Chroma)
- LangChain
- GitHub Repositories

## 📌 Use Cases
- Developer onboarding
- Code reviews and maintenance
- Understanding legacy code
- Faster debugging and exploration

## 👥 Team
Built as part of ''Gen AI 4 Gen Z Hackathon 2026''.

## 📄 License
This project is licensed under the MIT License.




