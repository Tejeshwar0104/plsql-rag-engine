# 🟦 PLSQL RAG Engine

A Retrieval-Augmented Generation (RAG) system designed to perform intelligent semantic search and question-answering on PL/SQL documents using vector embeddings and a lightweight LLM.

## 📌 Overview

This project processes PL/SQL documentation, converts it into embeddings, stores them in a FAISS vector database, and retrieves the most relevant chunks based on a user query.  
A language model then uses the retrieved context to generate accurate, PL/SQL-specific answers.

This acts as an AI-powered **PL/SQL knowledge assistant**.

## 🚀 Features

- 📄 PL/SQL documentation ingestion  
- ✂️ Text chunking system  
- 🧠 Embedding generation (Gemma Embeddings / any chosen model)  
- ⚡ FAISS vector search  
- 🔍 Intelligent semantic retrieval  
- 🤖 RAG pipeline (Query → Retrieve → Generate)  
- 📘 Fully implemented in Jupyter Notebook  
- 📦 Pre-saved embeddings & indexes included  

## Tech Stack

- **Python**
- **FAISS** 
- **Embedding Model** 
- **Jupyter Notebook**  

Note: Kindly run in Colab TPU or System with 12+ GB RAM. 
