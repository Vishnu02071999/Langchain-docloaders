# Langchain-docloaders
This repository demonstrates how to use LangChain Document Loaders to ingest data from different document formats and prepare it for Large Language Model (LLM) applications.

# Overview

The repository contains 3 examples:

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

Uses WebBaseLoader to:

- Load content directly from a web page using its URL.
- Extract the page's text content along with metadata (such as title, source URL, and description).
- Convert the webpage into LangChain Document objects for further processing.
- Pass the extracted content to an OpenAI model.


# Technologies Used
- LangChain
- OpenAI GPT Models
- PyPDFLoader
- TextLoader
- WebBaseLoader
- Prompt Templates
- Output Parsers
- Python
- dotenv

# Learning Outcomes

By completing this project, you will learn:

- What Document Loaders are in LangChain.
- How to load PDF documents into LangChain.
- How to load plain text files.
- How to use WebBaseLoader to fetch and process website content.
- How document content and metadata are stored.
- How to connect loaded documents to LLM workflows.
- How to build simple document summarization pipelines.

 # Key Concept
Document Loaders act as the first step in many LangChain pipelines. They transform external data sources such as PDFs, text files, web pages, and databases into LangChain Document objects that can be processed, split, embedded, stored in vector databases, and used in RAG applications.
