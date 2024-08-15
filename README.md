# Chatbot Application
URL for the chatbot : https://chatbot-go.streamlit.app/

## Description

This project is a chatbot application that processes PDFs and answers questions using a Retrieval-Augmented Generation (RAG) approach. It includes functionality for handling PDF documents, text splitting, and integration with external APIs.

## Features
1. User Interface (UI)
   Streamlit Frontend:
   Provides the user interface where users can upload PDFs, input questions, and view results. Includes interactive elements such as file uploaders, text inputs, and buttons.
2. PDF Processing
   PDF Extraction: Reads the uploaded PDF file and extracts its text content.
   Text Processing: Splits the extracted text into manageable chunks.
4. Vector Database
   Vector Store: Stores the text chunks in a vector database for fast retrieval. Uses embeddings to represent the chunks in a high-dimensional space.
5. Embeddings and Model Interaction
   Ollama Embeddings: Converts text chunks into vector embeddings for efficient similarity search.
   LLM (Large Language Model): Processes queries and generates responses based on the retrieved information from the vector store.
6. Retrieval-Augmented Generation (RAG)
   Multi-Query Retriever: Generates multiple variations of a user’s query to improve the retrieval of relevant documents from the vector database.
   Response Generation: Uses the retrieved documents to generate an answer to the user’s question.
7.Cleanup
   Vector Database Cleanup: Deletes the stored data from the vector database when no longer needed.

## Installation

### Prerequisites

- Python 3.8 or higher
- Virtual environment (recommended)
  
## Features of this APP
   File Uploader: Allows users to upload a PDF file.
   Text Extraction and Processing: Processes the PDF file to create chunks and stores them in a vector database.
   Question Input: Users can input questions related to the PDF.
   Answer Retrieval: Uses the RAG (Retrieval-Augmented Generation) model to provide answers based on the uploaded PDF.
   Cleanup Button: Deletes the vector database collection to free up resources.
   This setup provides an interactive web interface for your document processing and question-answering system.
