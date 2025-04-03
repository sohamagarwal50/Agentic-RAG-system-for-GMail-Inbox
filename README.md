# Agentic RAG System for Gmail

## Overview
This **Agentic Retrieval-Augmented Generation (RAG) System** enables users to interact with their Gmail inbox through a conversational AI. It leverages **LangChain, Gemini, and the Gmail API** to load emails into a vector database, providing **context-aware, agentic responses** to queries about your inbox.

## Features
- **Email Retrieval:** Loads Gmail inbox as a vector database.
- **Conversational Search:** Enables natural language querying of emails.
- **Agentic Behavior:** Uses agentic behaviour to break down complex queries for better accuracy.
- **Context-Aware Responses:** Generates relevant, insightful answers using **retrieved email context**.

## Tech Stack
- **LangChain** – Manages RAG pipeline and agent behavior.
- **Gemini API** – Powers response generation.
- **Gmail API** – Fetches emails and loads them into a vector database.
- **Vector Database** – Stores email embeddings for efficient retrieval.

## How It Works
1. **Email Ingestion**: Fetches emails from Gmail and converts them into vector embeddings.
2. **Query Processing**: Interprets user queries using an AI agent.
3. **Retrieval**: Searches the vector database for relevant email content.
4. **Response Generation**: Uses Gemini API to craft responses based on retrieved context.
5. **Agentic Refinement**: Breaks down complex queries and iteratively improves responses.

## Installation
```bash
# Clone the repository
git clone https://github.com/your-username/agentic-rag-gmail.git
cd agentic-rag-gmail

# Create a virtual environment
conda create --name rag_gmail python=3.10
conda activate rag_gmail

# Install dependencies
pip install -r requirements.txt
```

## Usage
Type your queries, and the AI will retrieve relevant email data to generate responses.

## Future Improvements
- Enhancing multi-turn conversation memory.

## Contributing
Contributions are welcome! Feel free to submit pull requests or open issues.
