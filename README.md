# 🤖 Chat with PDF Locally using Ollama + LangChain

A powerful local **Retrieval-Augmented Generation (RAG)** application that enables you to interact with your PDF documents using **Ollama** and **LangChain**. This project provides both a **Jupyter notebook** for experimentation and a **Streamlit web interface** for easy interaction.

[![Python Tests](https://github.com/tonykipkemboi/ollama_pdf_rag/actions/workflows/tests.yml/badge.svg)](https://github.com/tonykipkemboi/ollama_pdf_rag/actions/workflows/tests.yml)

---

## 📁 Project Structure

```bash
ollama_pdf_rag/
├── src/                      # Source code
│   ├── app/                  # Streamlit application
│   │   ├── components/       # UI components
│   │   │   ├── chat.py       # Chat interface
│   │   │   ├── pdf_viewer.py # PDF display
│   │   │   └── sidebar.py    # Sidebar controls
│   │   └── main.py           # Main app
│   └── core/                 # Core functionality
│       ├── document.py       # Document processing
│       ├── embeddings.py     # Vector embeddings
│       ├── llm.py            # LLM setup
│       └── rag.py            # RAG pipeline
├── data/                     # Data storage
│   ├── pdfs/                 # PDF storage
│   │   └── sample/           # Sample PDFs
│   └── vectors/              # Vector DB storage
├── notebooks/                # Jupyter notebooks
│   └── experiments/          # Experimental notebooks
├── tests/                    # Unit tests
├── docs/                     # Documentation
└── run.py                    # Application runner

---
## ✨ Key Features

- **🔒 Full Local Processing:** All processing happens locally—no data leaves your machine.
- **📄 PDF Processing:** Breaks down PDFs into manageable chunks for efficient processing.
- **🧠 Multi-query Retrieval:** Handles multiple queries to improve understanding and provide contextually relevant responses.
- **🎯 Advanced RAG Implementation:** Uses LangChain's RAG pipeline to retrieve answers intelligently.
- **🖥️ Streamlit Web Interface:** A simple and easy-to-use web-based interface for chatting with your PDF.
- **📓 Jupyter Notebooks for Experimentation:** Experiment with the model and retrieval pipeline in an interactive notebook environment.

---
