# Langchain-docloaders
This repository demonstrates how to use LangChain Document Loaders to ingest data from different document formats and prepare it for Large Language Model (LLM) applications.

# Overview

The project contains 2 examples:

1. PDF Document Loading

Uses PyPDFLoader to:

- Load a PDF document.
- Extract page-wise content.
- Access document metadata.
- Inspect the structure of loaded documents.

Uses TextLoader to:

- Load text data from a .txt file.
- Extract content and metadata.
- Pass the loaded text to an OpenAI model.
- Generate a concise summary using LangChain chains.

# Technologies Used
- LangChain
- OpenAI GPT Models
- PyPDFLoader
- TextLoader
- Prompt Templates
- Output Parsers
- Python
- dotenv

# Learning Outcomes

By completing this project, you will learn:

- What Document Loaders are in LangChain.
- How to load PDF documents into LangChain.
- How to load plain text files.
- How document content and metadata are stored.
- How to connect loaded documents to LLM workflows.
- How to build simple document summarization pipelines.

 # Key Concept
Document Loaders act as the first step in many LangChain pipelines. They transform external data sources such as PDFs, text files, web pages, and databases into LangChain Document objects that can be processed, split, embedded, stored in vector databases, and used in RAG applications.
