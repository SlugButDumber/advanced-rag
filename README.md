This is an implementation of a RAG system with a few improvements:
  1. We utilized a hybrid retrieval strategy using FAISS for embedding-space search and BM25 for keyword-matching
  2. We implemented a Re-ranking algorithm using BGE Reranker for more relevent context retention
  3. We created a memory-aware pipeline which also takes into account the chat history of the RAG, creating a heirerchical relation among a series of prompts and answers

Collaborators:
  1. Arhat Amitabh, Student at Dept. of Electrical Engineering, IIT Kharagpur
  2. Salil Lokhande, Student at Dept. of Mechanical Engineering, IIT Kharagpur
