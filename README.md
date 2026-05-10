# Build a Semantic Book Recommender with LLMs

## Introduction
This repository contains the complete implementation of a **Semantic Book Recommendation System** powered by **Large Language Models (LLMs)**.

The project demonstrates how to build an intelligent recommendation engine that understands natural language queries and suggests relevant books based on semantic similarity.

For example, users can search with prompts such as:

> "A book about a person seeking revenge"

and receive contextually relevant book recommendations.

---

# Project Components

This project includes the following main components:

### 1. Text Data Cleaning
- Load and preprocess raw book data
- Clean missing or inconsistent values
- Prepare text fields for embedding generation

---

### 2. Semantic Search & Vector Database
- Convert book descriptions into vector embeddings
- Build a vector database for similarity search
- Retrieve books based on semantic meaning rather than exact keywords

---

### 3. Web Application with Gradio
- Create an interactive user interface using Gradio
- Allow users to enter natural language queries
- Display personalized book recommendations


---

# Environment Variables

To create the vector database, you need an OpenAI API key.

Create a `.env` file in the root directory and add:

```env
OPENAI_API_KEY=your_api_key_here
```

---

# Requirements

All project dependencies are included in:

```text
requirements.txt
```

---

# Expected Outcome

By the end of this project, you will have:

- A semantic search engine for books
- A vector database built from book embeddings
- A fully functional book recommendation web app
- Practical experience with LLM-powered applications
