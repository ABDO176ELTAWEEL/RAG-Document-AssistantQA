# RAG-Document-AssistantQA
"An intelligent RAG-based QA system using Llama 3 and ChromaDB for context-aware document interaction and hallucination mitigation."
# 🤖 Smart RAG-Based Document Assistant

# Welcome Dr.Rahatara Ferdousi
# This is Group 19's Project: RAG-Based Document Assistant
# Please run the cells in order to initialize the environment and the UI.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO_NAME/blob/main/YOUR_NOTEBOOK_NAME.ipynb)

An intelligent question-answering system based on **Retrieval-Augmented Generation (RAG)** designed to interact with PDF documents with high factual accuracy.

## 📖 Project Overview
This project delivers accurate and context-aware responses by grounding generation in retrieved evidence from uploaded documents. It is specifically designed to mitigate hallucinations and improve reliability in real-world generative AI applications.

## 🛠️ Methodology & Architecture
The system follows a modular pipeline:
1. **Ingestion**: Loading and preprocessing PDF documents.
2. **Chunking**: Semantic chunking using Recursive Text Splitter to preserve context.
3. **Vector Store**: Storage and similarity search using **ChromaDB**.
4. **Generation**: Response generation using **Llama 3** (via Ollama) conditioned on retrieved context.

## 🚀 Key Features
- **Multi-PDF Support**: Upload and query multiple documents simultaneously.
- **Executive Summary**: One-click professional summary of the entire document collection.
- **Chat Memory**: Maintains conversation context for natural follow-up questions.
- **Source Citations**: Every answer includes the exact page number and source for full transparency.

## 💻 Tech Stack
- **Language**: Python
- **LLM**: Llama 3 (via Ollama)
- **Framework**: LangChain
- **UI**: Gradio
- **Embeddings**: HuggingFace Multilingual MiniLM

## 🏁 How to Run
1. Click the **Open In Colab** badge at the top of this page.
2. Run the installation cell to setup **Ollama** and all required dependencies.
3. Launch the **Gradio** interface from the last cell.
4. Upload your PDF files, click **Analyze**, and start interacting with your data!

## 👥 Group 19 Members
* **Abdelrahman Ibrahim**
* **Aya Noah**

---
*This project was developed as part of the Generative AI course (CSAI810) to demonstrate proficiency in embedding-based retrieval and modular system design.*
