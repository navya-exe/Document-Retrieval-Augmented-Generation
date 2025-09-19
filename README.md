# Document-Retrieval-Augmented-Generation
Chat with your documents using RAG! A Retrieval-Augmented Generation pipeline that connects Large Language Models with your PDFs to deliver accurate, context-aware answers.
Docu-RAG is a Retrieval-Augmented Generation (RAG) pipeline that allows users to chat with their documents (PDFs, text files, manuals, etc.) using a Large Language Model (LLM).

🔹 Problem: Traditional LLMs (like GPT) are limited to their training data and can hallucinate when asked domain-specific or private questions.

🔹 Solution: This project connects an LLM to your own documents using embeddings + a vector database. When a user asks a question, the system retrieves the most relevant chunks from the documents and generates accurate, context-aware answers.

🚀 Features

Upload and process PDF documents
Convert text into semantic embeddings using sentence-transformers
Store and search embeddings with FAISS
Retrieval-Augmented answers from LLM
Simple Streamlit app for interactive Q&A

🛠️ Tech Stack

Python
Sentence-Transformers → embeddings
FAISS → vector database for similarity search
PyPDF2 → extract text from PDFs
NLTK → text preprocessing
Streamlit → chat UI
