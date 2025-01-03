# Hybrid-Search-RAG

**Hybrid Search with LangChain & Pinecone**
This repository demonstrates an implementation of Hybrid Search using LangChain and Pinecone Vector Database. Hybrid search is a robust search methodology that combines multiple search techniques, such as traditional keyword-based searching, semantic search, and advanced machine learning models, to provide accurate and context-aware results.

**Overview**
Hybrid Search blends:

_Semantic Search:_ Utilizes dense vector representations (embeddings) of text for similarity-based retrieval.
_Syntactic Search:_ Employs exact keyword or sparse vector searches like TF-IDF, Bag of Words, etc.
The combination of these methods ensures a more versatile and powerful search mechanism, catering to a wide range of user queries and data types.

**Key Features**
_Dense Vector Embeddings_: Generated using OpenAI models, Hugging Face embeddings, or similar tools.
_Sparse Matrix Representations:_ Includes TF-IDF, Bag of Words, and other traditional methods.
_Hybrid Scoring:_ Combines semantic and syntactic scores using techniques like reciprocal rank fusion and weighted aggregation.
_RAG (Retrieval-Augmented Generation):_ Augments responses by feeding retrieved data into a large language model (LLM).



![Hybrid Vector Search Tech 1](https://github.com/user-attachments/assets/cdff7c4d-d8a5-478d-8a62-08d9d8b9231c)
![Hybrid Vector Search Tech 2](https://github.com/user-attachments/assets/9648ef73-2482-4277-86f9-37c545f2f91c)
![Hybrid Vector Search Tech 3](https://github.com/user-attachments/assets/9048d1bf-92fb-4ae6-9b7f-9ef6dc39e2c7)
