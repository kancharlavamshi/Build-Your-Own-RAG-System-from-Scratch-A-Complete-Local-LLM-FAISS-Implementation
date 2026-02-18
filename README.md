Build Your Own RAG System from Scratch
A Complete Local LLM + FAISS Implementation
<p align="center"> <img src="coverpage.jpg" alt="RAG System Architecture" width="100%"> </p>

Overview

This project demonstrates how to build a Retrieval-Augmented Generation (RAG) system from scratch using:
🤖 Local LLM (TinyLlama / Transformers)

🔍 FAISS Vector Search

🧠 BGE Embeddings (GPU-Accelerated)

📄 PDF Course Material

⚡ Fully Local Inference (No APIs)

The system converts raw course notes into a context-aware AI study assistant.

## System Architecture

PDF Course Notes

        ↓
Text Extraction (PyPDF)

        ↓
Chunking (with overlap)

        ↓
Embedding Model (BGE)

        ↓
FAISS Vector Index

        ↓
User Question

        ↓
Query Embedding

        ↓
Top-K Relevant Chunks

        ↓
Local LLM (Transformers) 


## 🛠 Tech Stack

Python 3.12

PyTorch (CUDA)

HuggingFace Transformers

Sentence-Transformers (BGE-large)

FAISS (GPU)

PyPD
        ↓
Context-Aware Answer 

# 📌 License
This repository contains only code.
Course materials should be downloaded separately according to their respective licenses.

# ⭐ Star This Repo
If this project helped you understand RAG from scratch, consider starring it.
