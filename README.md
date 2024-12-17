# Improve RAG accuracy 

Context
You are tasked with improving the accuracy of a Retrieval-Augmented Generation (RAG) system used to answer questions based on a set of articles. The current system retrieves relevant documents using a dense vector search and generates responses using a pre-trained language model. However, its accuracy in providing relevant and coherent answers needs improvement.

Tasks:
1. Use the dataset (https://docs.google.com/spreadsheets/d/1yfPygE3UztXA2j767_oBtBVKcyOTZvuUYOs1sbvJfqg/edit?usp=sharing) to build the LLM embeddings-based RAG system. 
2. Evaluation datasets:
 - Here are synthetic Q&As generated from the knowledge corpus: /datasets/synthetic_questions.csv.
     - Precision@k (k=2, k=5) based on synthetic Q&As using RAGAS, should be better than 0.55 
 - List of real-world Questions (with expected articles) is here: /datasets/real_questions.csv. 
3. Improve the RAG system accuracy further using any combination of approaches. Hints: keyword search, Knowledge Graphs, query expansion, etc...
4. The goal is to reach maximum possible accuracy improvements. Show results for each evaluation dataset separately: synthetic data and real-world data.
5. At least one of the experiments should be based on "openai-text-3-small-embeddings" (located here: https://drive.google.com/file/d/1mZRcNpCSHWwaBtvwTAUnphWZACq-ya9n/view?usp=sharing).

NOTE: 
- You can use any RAG framework and LLM of your choice. However, make sure to keep the same LLM throughout the assignment. 
- Use chunk sizes of 1000
- Use top 5 chunks for answer generation
- Your approach must be generally applicable
- Feel free to use any Vector DB / Solution

Deliverables
- Code: A Jupyter notebook (or equivalent Python script) with your solution.
- Report: A concise report (max 2 pages) explaining your approach, results, and future recommendations.
- Validation: Provide metrics (e.g., NDCG@k,  precision@k, BLEU, ROUGE) to demonstrate improved accuracy.
- Documentation: Clearly comment your code and provide instructions for replication.

Good luck! If you have any questions, please feel free to reach out to kairat@kodif.ai (cc: norm@kodif.ai) for clarifications.
