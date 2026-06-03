RAG Chatbot using Flowise

A Retrieval-Augmented Generation (RAG) chatbot built with Flowise that allows users to interact with documents through natural language queries. The chatbot retrieves relevant information from uploaded documents and generates context-aware responses using Large Language Models (LLMs).

---

Project Overview

This project demonstrates the implementation of a RAG pipeline using Flowise. The chatbot can:

* Load and process documents
* Split text into manageable chunks
* Generate embeddings for semantic search
* Store document vectors in a vector database
* Retrieve relevant context based on user queries
* Generate accurate answers using an LLM
* Maintain conversational memory

---

Architecture

```text
Document Upload
       │
       ▼
File Loader
       │
       ▼
Recursive Character Text Splitter
       │
       ▼
Google Gemini Embeddings
       │
       ▼
In-Memory Vector Store
       │
       ▼
Retriever
       │
       ▼
Conversational Retrieval QA Chain
       │
       ▼
Mistral AI
       │
       ▼
Response to User
```

---

 Tech Stack

* Flowise
* Google Gemini Embeddings
* Mistral AI
* Conversational Retrieval QA Chain
* In-Memory Vector Store
* Recursive Character Text Splitter

---

 Features

*  Document Question Answering
*  Semantic Search
*  Conversational Memory
*  AI-Powered Responses
*  Retrieval-Augmented Generation (RAG)
*  Fast and Visual Workflow Development

---

Workflow Components

1. File Loader

Loads and processes document files.

2. Recursive Character Text Splitter

Splits large documents into smaller chunks for efficient retrieval.

3. Google Gemini Embeddings

Converts text chunks into vector embeddings for semantic search.

4. In-Memory Vector Store

Stores document embeddings and retrieves relevant chunks.

5. Buffer Memory

Maintains chat history and conversational context.

6. Mistral AI

Generates intelligent responses based on retrieved context.

7. Conversational Retrieval QA Chain

Combines retrieval and generation to answer user questions accurately.

---

Example Questions

Users can ask:

* What is this document about?
* Summarize the document.
* Who is mentioned in the document?
* Explain the main concepts discussed.
* What are the key points?

---

What I Learned

Through this project, I gained practical experience with:

* Retrieval-Augmented Generation (RAG)
* Embeddings and Semantic Search
* Vector Databases
* Prompt Engineering
* Conversational AI
* LLM Integration
* Flowise Workflow Design

---

Acknowledgements

Built using Flowise, Google Gemini Embeddings, and Mistral AI to explore modern Retrieval-Augmented Generation architectures.
