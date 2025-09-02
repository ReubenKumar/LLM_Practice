This repository contains scripts that I’ve created while working with Large Language Models (LLMs).

📂 bet365_LLM_practise

This project demonstrates a simple Retrieval-Augmented Generation (RAG) pipeline:

SentenceTransformers → encodes Bet365-specific documents into vector embeddings.

Hugging Face Transformers → retrieves the most relevant context and generates a final answer.

The system takes a user query, finds the most relevant Bet365-specific context from the document set, and produces an answer using a pretrained language model.