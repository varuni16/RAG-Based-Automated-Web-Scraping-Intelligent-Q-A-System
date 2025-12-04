# RAG-Based-Automated-Web-Scraping-Intelligent-Q-A-System
A complete RAG pipeline that scrapes websites using Selenium, processes the text with LangChain, embeds it using HuggingFace models, and stores it in ChromaDB for semantic search and question-answering on real-time web data.

This project demonstrates a complete Retrieval-Augmented Generation (RAG) workflow built using web-scraped data. It extracts information from dynamic websites using Selenium, processes the text with LangChain, generates vector embeddings using HuggingFace models, and stores them in ChromaDB for semantic search and LLM-based question answering.

It serves as a practical guide to building real-time, data-aware AI systems.

# FEATURES

Dynamic Web Scraping – Extracts content from JavaScript-rendered pages using Selenium WebDriver.

Smart Text Chunking – Uses LangChain’s RecursiveCharacterTextSplitter for clean, optimized chunks.

High-Quality Embeddings – Employs HuggingFace/SentenceTransformer embeddings for semantic understanding.

Vector Database (ChromaDB) – Stores embeddings for fast similarity search and retrieval.

RAG Pipeline – Combines retrieved context with LLMs for accurate, grounded Q&A.

Notebook-Friendly – Fully implemented in a Jupyter Notebook with step-by-step workflow.

# TECH STACK

Python

Selenium

LangChain

ChromaDB

HuggingFace Embeddings

LLMs (ChatGPT, Llama, etc.)

# PROJECT WORKFLOW

Scrape Website Data

Selenium opens the target site

Extracts visible text from DOM

Preprocess & Chunk Text

Clean HTML → raw text

Chunk using LangChain splitters

Generate Embeddings

Use HuggingFace Embedding models

Convert chunks into vectors

Store in ChromaDB

Persist vector store

Enable similarity search

Build Retrieval + LLM Chain

Query → retrieve relevant chunks

Provide context to LLM

LLM answers based on web-scraped knowledge
