# rag-project
Retrieval-Augmented Generation


# Retrieval-Augmented Generation (RAG) Project

This project implements a basic RAG pipeline using both ChromaDB and Elasticsearch as vector databases.

## Key Features
- Document embedding with `sentence-transformers`
- Vector search with `ChromaDB` or `Elasticsearch`
- Text generation using Hugging Face Transformers
- Modular and notebook-friendly

## Usage
- Run `notebooks/rag_pipeline.ipynb` to try the full pipeline
- Choose your retriever backend: Chroma or Elasticsearch

## Setup
```bash
pip install -r requirements.txt
