# Mini RAG Chatbot

## Overview

This project implements a Mini RAG (Retrieval-Augmented Generation) Chatbot using:

* LangChain
* FAISS
* HuggingFace Embeddings
* Transformers

The chatbot can answer questions from a PDF document using semantic search and LLM-based response generation.

---

## Features

* PDF text extraction
* Text chunking
* Embedding generation
* FAISS vector database
* Semantic similarity search
* Context retrieval
* Prompt engineering
* LLM-based question answering

---

## Technologies Used

* Python
* LangChain
* FAISS
* HuggingFace Transformers
* Sentence Transformers
* PyPDF

---

## Project Workflow

1. Load PDF
2. Split text into chunks
3. Generate embeddings
4. Store vectors in FAISS
5. Retrieve relevant chunks
6. Send context to LLM
7. Generate final answer

---

## How to Run

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

Open:

```text
Mini_RAG_Chatbot.ipynb
```

---

## Sample Questions

* What is Deep Learning?
* Explain Transformer Architecture.
* What are embeddings?

---

## Future Improvements

* Streamlit UI
* Multiple PDF support
* Conversational memory
* OpenAI API integration
