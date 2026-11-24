# ChromaDB – Vector Database
## Project Overview
Implemented hands-on applications using **ChromaDB**, an open-source vector database, to explore document storage, embedding generation, semantic search, and efficient data retrieval for AI and RAG-based applications.

## Key Implementations

- **ChromaDB Client Implementations:** Worked with different ChromaDB clients, to understand persistent and in-memory vector database operations.

- **Collection Management:** Created, configured, and managed collections for organizing and storing document embeddings.

- **Document Storage:** Implemented document insertion using `add()` with unique IDs, document content, and custom metadata.

- **Custom Embedding Models:** Integrated pre-trained embedding models using Sentence Transformers and Hugging Face to generate custom document embeddings.

- **Semantic Search:** Implemented similarity-based document retrieval using `query()` and cosine similarity to identify contextually relevant information.

- **Metadata Filtering:** Applied filtering operations using `where` and `where_document` with operators such as `$and`, `$eq`, `$gt`, `$lt`, and `$contains`.

- **Data Retrieval:** Used `get()` to retrieve stored documents, IDs, metadata, and embeddings based on specified conditions.

- **Update Operations:** Implemented document and metadata modifications using `update()`.

- **Delete Operations:** Managed collection data by deleting specific records using `delete()`.

## Technologies & Libraries
- Python
- ChromaDB
- Sentence Transformers
- Hugging Face
- NumPy
- Pandas
- Google Colab

## Key Learning Outcomes
- Understanding vector databases and embedding-based storage.
- Practical implementation of semantic search and similarity-based retrieval.
- Working with custom embedding functions and pre-trained models.
- Understanding core CRUD operations in ChromaDB.
- Exploring vector database concepts used in Retrieval-Augmented Generation (RAG) applications.
