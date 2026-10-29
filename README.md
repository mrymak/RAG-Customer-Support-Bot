# RAG-Based Customer Support Assistant

This project implements a Retrieval-Augmented Generation (RAG) pipeline to answer e-commerce FAQs.

Technologies Used:
- Embeddings: Sentence-Transformers (all-MiniLM-L6-v2)
- Vector Database: FAISS
- Language Model: FLAN-T5-small
- Environment: Google Colab (Python)

Features:
- Retrieves top-3 relevant policy documents.
- Generates grounded answers without hallucinations.
- Fast response time (Average: 0.44 seconds per query).
- Live Web UI using Gradio.

How to Run:
Open the .ipynb file in Google Colab and run all cells sequentially.
