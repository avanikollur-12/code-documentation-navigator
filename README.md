# Code Documentation Navigator

A simple Python Streamlit app that analyzes Python code and generates a **navigable structure** of functions, classes, and imports.  
This tool helps developers and learners quickly understand unfamiliar code.

---

## 🛠️ Getting Started

Follow these steps to run the Code Navigator locally.

### Requirements
- Python 3.11 or higher
- Streamlit library

### Installation
1. Clone the repository (or download as ZIP):
   ```bash
   git clone https://github.com/avanikollur-12/code-documentation-navigator.git
   cd code-documentation-navigator
Install Streamlit:

pip install streamlit
Running the App
Open a terminal or PowerShell in the project folder.

Run the Streamlit app:

streamlit run app.py
A browser window should open automatically.
If not, open your browser and go to:

http://localhost:8501
Using the App
Paste any Python code into the text area.

Click Analyze Code.

View detected functions, classes, and imports in the sidebar.

🚀 Features
Detects functions and classes in Python code

Lists imports

Shows line numbers for navigation

Easy-to-use Streamlit interface

Lightweight and fast

📌 Notes
Works best with Python source files

Make sure file names are correct (app.py and parser.py)

Can be extended with explanations or TL;DR summaries per function

🎬 Demo 
Demo Video:

💡 Future Improvements
Add AI-based explanations for each function/class

Multi-language code support

Search and filter features for large projects

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




