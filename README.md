# Mini RAG LLM

Mini RAG LLM is a simple Retrieval-Augmented Generation (RAG) application built using Python, Streamlit, Sentence Transformers, ChromaDB, and Ollama.

The application allows users to paste a document, convert it into embeddings, store the data in ChromaDB, retrieve the most relevant chunks based on a question, and generate an answer using the Llama 3.2 model through Ollama.

## Features

- Paste and process custom document text
- Split documents into smaller chunks
- Generate embeddings using Sentence Transformers
- Store embeddings in ChromaDB
- Perform similarity search
- Retrieve relevant document chunks
- Generate answers using Ollama
- Display the retrieved context
- Simple Streamlit interface

## Tech Stack

- Python
- Streamlit
- Sentence Transformers
- ChromaDB
- Ollama
- Llama 3.2

## How It Works

Document → Text Chunking → Embeddings → ChromaDB → User Question → Similarity Search → Relevant Chunks → Context → Ollama → Answer

## How to Run

```bash
pip install -r requirements.txt
ollama pull llama3.2
streamlit run app.py
