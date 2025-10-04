# Book Recommender LLM

A Book Recommender LLM uses AI to suggest books based on user queries. It leverages embeddings and similarity search to provide personalized recommendations.

## Features

- Personalized book recommendations based on user queries.
- Embedding-based search using LangChain, HuggingFaceEmbeddings, and Chroma.
- Scalable and efficient document retrieval.

## Tech Stack

- **LangChain**: For embedding and similarity search.
- **Chroma**: For storing and retrieving embeddings.
- **HuggingFaceEmbeddings**: To generate vector representations of text.
- **Python**: Backend development.

## Installation

1. Clone the repo:

   ```bash
   git clone https://github.com/kitessafikadu/book-recommender.git
   cd book-recommender
   ```

2. Set up the environment:

   ```bash
   python -m venv .venv
   .venv\Scripts\activate  # Windows
   source .venv/bin/activate  # macOS/Linux
   pip install -r requirements.txt
   ```
