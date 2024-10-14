# Simple Retrieval-Augmented Generation (RAG) System

This repository demonstrates a simple Retrieval-Augmented Generation (RAG) system built using **LangChain**, **ChromaDB**, and **Ollama** in Google Colab. The project retrieves relevant document content, processes queries, and generates responses using an LLM model, improving the quality of responses through augmented retrieval.

## Overview

RAG systems combine the power of information retrieval (IR) and large language models (LLMs) to generate context-aware, accurate, and detailed answers to user queries. This system loads documents, splits them into chunks, generates embeddings for similarity search, and uses an LLM for final query responses based on document context.

The system is implemented in Google Colab, and all dependencies are installed and run within the Colab environment. We use the **Mistral** model for LLM inference and **nomic-embed-text** for embeddings in this example.

## Features

- Document ingestion from PDF.
- Text splitting into manageable chunks.
- Embedding-based document retrieval using **ChromaDB**.
- Query augmentation for better retrieval using **MultiQueryRetriever**.
- Query answering using an LLM model hosted by **Ollama**.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- A **Google Colab** account.
- Python 3.x (comes preinstalled in Colab).
- Internet access to pull models from Ollama.
- Basic understanding of Python, LLMs, and Google Colab notebooks.
