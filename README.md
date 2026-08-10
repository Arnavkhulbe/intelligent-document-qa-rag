# Intelligent Document Question Answering System using RAG

A Retrieval-Augmented Generation (RAG) application built using Python, LangChain, ChromaDB, Hugging Face embeddings, and Groq LLM.

## Project Workflow

Document
↓
Document Loader
↓
Text Splitting
↓
Embeddings
↓
ChromaDB Vector Store
↓
Similarity Search
↓
Relevant Context
↓
Groq LLM
↓
Generated Answer

## Technologies Used

- Python
- LangChain
- ChromaDB
- Hugging Face Sentence Transformers
- Groq
- Google Colab

## Features

- Loads documents
- Splits documents into smaller chunks
- Creates vector embeddings
- Stores embeddings in ChromaDB
- Retrieves relevant document chunks
- Uses Groq LLM to generate answers based on retrieved context

## How to Run

1. Open `RAG_Project.ipynb` in Google Colab.
2. Install the required dependencies.
3. Upload the document.
4. Enter your own Groq API key when prompted.
5. Run the notebook cells in order.
6. Ask questions about the document.

## API Key

The API key is **not stored in this repository**.

The notebook asks the user to enter their own Groq API key securely using `getpass()`.

## Project Type

Generative AI / Retrieval-Augmented Generation (RAG)
