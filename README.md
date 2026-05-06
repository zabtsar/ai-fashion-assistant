# AI Fashion Assistant System

An AI-powered fashion recommendation assistant built using Langflow, Astra DB, and Google Generative AI Embeddings. This project uses Retrieval-Augmented Generation (RAG) to provide smarter and more relevant fashion recommendations based on uploaded reference documents.

---

## Project Overview

The purpose of this project is to create an intelligent fashion assistant that can:

* Understand fashion-related documents
* Store document embeddings in a vector database
* Retrieve relevant information using semantic search
* Generate personalized fashion recommendations
* Answer user questions through a chat-based assistant

This system helps users receive better outfit suggestions, styling advice, and fashion insights using AI.

---

## Features

* Upload PDF or document references
* Automatic text chunking using Split Text
* Embedding generation using Google Generative AI
* Vector storage using Astra DB
* Semantic similarity search
* Prompt-based AI response generation
* Chat interface for user interaction
* Memory support for better conversation context

---

## Tech Stack

### Backend / AI Workflow

* Langflow
* Python
* RAG (Retrieval-Augmented Generation)

### Database

* Astra DB (Vector Database)

### Embeddings

* Google Generative AI Embeddings

### LLM

* Gemini / Google Generative AI

---

## System Flow

### Flow 1 — Document Ingestion

1. Upload fashion reference document
2. Split text into smaller chunks
3. Generate embeddings
4. Store embeddings into Astra DB

### Flow 2 — Fashion Assistant Chatbot

1. User sends a question
2. Search relevant documents from Astra DB
3. Parse retrieved context
4. Build prompt using Prompt Template
5. Send prompt to Language Model
6. Return final response to Chat Output

---

## Project Structure

```text
ai-fashion-assistant/
│
├── fashion-assistant-langflow.json
├── README.md
├── .gitignore
│
├── screenshots/
│   ├── flow-diagram.png
│   ├── chat-output.png
│   └── astra-db.png
│
└── docs/
    └── project-documentation.pdf
```

---

## Example Use Cases

* “What outfit matches black cargo pants?”
* “Suggest casual outfits for campus”
* “What colors match navy blue sneakers?”
* “Recommend minimalist fashion styles”

---

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/ai-fashion-assistant.git
cd ai-fashion-assistant
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment Variables

Create `.env` file:

```env
ASTRA_DB_TOKEN=your_token_here
GOOGLE_API_KEY=your_api_key_here
```

### Run Project

Open Langflow and import:

```text
fashion-assistant-langflow.json
```

---

## Screenshots

(Add your screenshots here)

* Langflow Flow Diagram
* Astra DB Collection
* Final Chat Result

---

## Future Improvements

* Frontend web interface
* User authentication
* Outfit image recommendations
* Real-time fashion trend integration
* Deployment to cloud platform
* Multi-language support

---

## Author

Zidan Absar Abdallah

Bachelor of Informatics Engineering
Universitas Pamulang

---

## License

This project is created for educational and portfolio purposes.
