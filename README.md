# Chroma DB Advanced Search and Embeddings

## Overview
This project explores how to use **Chroma DB** with **Python** for creating text embeddings and performing advanced vector-based searches.  
It shows how to store, embed, and query key-value data using the **SentenceTransformers** model for meaningful similarity and metadata-based searches.

---

## What I Did
I integrated **Chroma DB** with Python and set up an embedding function using `SentenceTransformerEmbeddingFunction`.  
Then I created a custom collection to store data and generate embeddings automatically when new entries are added.  
Finally, I built a function called `perform_advanced_search` to perform comprehensive searches — combining similarity search, metadata filtering, and multi-criteria queries.

---

## Key Learnings

- **Integrating vector data:** Learned how to treat structured key-value pairs as vector data and perform vector searches using Chroma DB.  
- **Generating embeddings:** Used the SentenceTransformers model to turn text data into embeddings automatically when added to a collection.  
- **Advanced search capabilities:** Implemented various search types, such as semantic similarity, metadata filtering, and combined filtering with similarity search.  
- **Function in focus:** The main search logic lives inside `perform_advanced_search`, which runs and displays results for multiple search modes.

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/DeepanshuTevathiya/Chroma-DB-and-embeddings.git
