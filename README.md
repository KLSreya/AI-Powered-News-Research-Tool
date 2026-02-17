📰 AI-Powered News Research Tool (RAG System)

An intelligent news research assistant built using LangChain that allows users to analyze multiple news articles and ask natural language questions to get accurate, source-backed answers using Retrieval-Augmented Generation (RAG).

📌 Overview

This project processes unstructured news articles from given URLs, converts them into vector embeddings, stores them in a vector database, and retrieves relevant information to answer user queries using a Large Language Model.

🚀 Features

Upload and process multiple news article URLs

Semantic search using vector similarity

Question answering with contextual accuracy

Source attribution for generated answers

Efficient retrieval using FAISS vector database

🧠 Architecture / Workflow

User provides news article URLs

Articles are loaded using an unstructured data loader

Text is cleaned and split into chunks

Chunks are converted into vector embeddings

Embeddings are stored in FAISS

User asks a question

Relevant chunks are retrieved via similarity search

LLM generates the final answer with sources

🛠️ Tech Stack

Language: Python

Framework: LangChain

Embeddings: OpenAI Embeddings

Vector Store: FAISS

Concepts: RAG, Semantic Search, Vector Databases

Tools: Jupyter Notebook, dotenv, Pickle
