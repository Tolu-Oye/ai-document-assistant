# AI Document Assistant (RAG)

## Overview
This project implements a Retrieval-Augmented Generation (RAG) system that allows users to query PDF documents using natural language.

## Features
- PDF ingestion and text extraction
- Text chunking with overlap
- Semantic search using embeddings and FAISS
- Context-aware answer generation using OpenAI LLM

## Tech Stack
- Python
- FAISS (vector database)
- Sentence Transformers (embeddings)
- OpenAI API (LLM)

## How it works
1. PDF → text extraction
2. Text → chunks
3. Chunks → embeddings
4. Stored in FAISS
5. Query → embedding → similarity search
6. Retrieved chunks + query → LLM → answer

## Example
User: "What is this document about?"

AI: Generates a response based on relevant sections of the document.
