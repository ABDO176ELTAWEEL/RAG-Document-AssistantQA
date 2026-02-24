# RAG-Document-AssistantQA
"An intelligent RAG-based QA system using Llama 3 and ChromaDB for context-aware document interaction and hallucination mitigation."
# 🤖 Smart RAG-Based Document Assistant

An intelligent question-answering system based on **Retrieval-Augmented Generation (RAG)** designed to interact with PDF documents with high factual accuracy.

## 📖 Project Overview
[cite_start]This project delivers accurate and context-aware responses by grounding generation in retrieved evidence from uploaded documents[cite: 6]. [cite_start]It is designed to mitigate hallucinations and improve reliability in real-world generative AI applications[cite: 7, 10].



## 🛠️ Methodology & Architecture
[cite_start]The system follows a modular pipeline[cite: 15]:
1. [cite_start]**Ingestion**: Loading and preprocessing PDF documents[cite: 16].
2. [cite_start]**Chunking**: Semantic chunking using Recursive Text Splitter[cite: 17].
3. [cite_start]**Vector Store**: Storage and similarity search using **ChromaDB**[cite: 18, 19].
4. [cite_start]**Generation**: Response generation using **Llama 3** conditioned on retrieved context[cite: 20].

## 🚀 Features
- **Multi-PDF Support**: Upload and query multiple documents simultaneously.
- **Executive Summary**: One-click professional summary of document content.
- **Chat Memory**: Maintains conversation context for follow-up questions.
- **Source Citations**: Every answer includes the exact page number for transparency.

## 💻 Tech Stack
- [cite_start]**Language**: Python [cite: 12]
- **LLM**: Llama 3 (via Ollama)
- **Framework**: LangChain
- **UI**: Gradio
- **Embeddings**: HuggingFace Multilingual MiniLM

## 🏁 How to Run
1. Open the notebook in **Google Colab**.
2. Run the installation cell to setup **Ollama** and dependencies.
3. Launch the **Gradio** interface.
4. Upload your files, click **Analyze**, and start chatting!

## 👥 Group Members
* [cite_start]**Abdelrahman Ibrahim** [cite: 1]
* [cite_start]**Aya Noah** [cite: 1]

---
[cite_start]*This project was developed for the Generative AI course to demonstrate proficiency in embedding-based retrieval and modular system design[cite: 9, 10].*
