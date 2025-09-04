# Retrieval-Augmented Generation (RAG) Pipeline from Scratch

## Overview

This project demonstrates a traditional Retrieval-Augmented Generation (RAG) pipeline, built from scratch using modern open-source libraries. The pipeline ingests PDF documents, splits them into meaningful chunks, generates high-quality embeddings, and stores them in a scalable vector database for efficient semantic search and retrieval.

## Features

- **Automated PDF Ingestion:** Load and process multiple PDF files.
- **Intelligent Text Chunking:** Split documents into optimal chunks for retrieval.
- **Embedding Generation:** Use Sentence Transformers to convert text into dense vector representations.
- **Vector Database Storage:** Store and retrieve embeddings using ChromaDB.
- **Semantic Search:** Retrieve relevant document chunks using similarity metrics.

## Tech Stack

- **Python**
- **LangChain** (document structure and processing)
- **Sentence Transformers** (embedding generation)
- **ChromaDB** (vector database with persistent storage)
- **scikit-learn** (similarity metrics)
- **Jupyter Notebook**

## Data

The pipeline processes a diverse set of PDF documents, enabling robust and context-aware knowledge retrieval for downstream applications.

## Installation

1. Clone this repository:
    ```
    git clone <your-repo-url>
    cd Building-RAG-Pipeline-From-Scratch
    ```

2. Install dependencies:
    ```
    pip install -r requirements.txt
    ```

## Usage

1. Place your PDF documents in the designated data folder.
2. Run the Jupyter Notebook or Python scripts to ingest, process, and index your documents.
3. Use the provided semantic search functions to query your knowledge base.

## Requirements

See [`requirements.txt`](requirements.txt) for the full list of dependencies.

## Acknowledgements

A special thanks to **Krish Naik** for his invaluable guidance and educational content, especially on LangChain’s Document Structure and best practices for building RAG pipelines.



**Keywords:** RAG, LangChain, ChromaDB, Python, AI, Document Retrieval, Embeddings, VectorDB, Krish Naik, Machine Learning,
