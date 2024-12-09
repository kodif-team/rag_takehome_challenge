# Improve RAG accuracy 

Context
You are tasked with improving the accuracy of a Retrieval-Augmented Generation (RAG) system used to answer questions based on a set of articles. The current system retrieves relevant documents using a dense vector search and generates responses using a pre-trained language model. However, its accuracy in providing relevant and coherent answers needs improvement.

Tasks:
1. Use the dataset (https://docs.google.com/spreadsheets/d/19RrrbXLjiVSzBrN67px3jz5H-aQI-eEpUJjwAFKLV9U/edit?usp=sharing) to build the basic vanilla embeddings-based RAG system. Link for question with embeddings (*openai-text-3-small-embeddings*)
https://drive.google.com/file/d/1mZRcNpCSHWwaBtvwTAUnphWZACq-ya9n/view?usp=sharing

2. Use questions.csv to test the accuracy of the vanilla RAG.
3. Improve the RAG system accuracy using any combination of approaches. Hints: keyword search, Knowledge Graphs, query expansion, etc...
NOTE: 
- You can use any RAG framework and LLM of your choice. However, make sure to keep the same LLM throughout the assignment. 

Deliverables
- Code: A Jupyter notebook (or equivalent Python script) with your solution.
- Report: A concise report (max 2 pages) explaining your approach, results, and future recommendations.
- Validation: Provide metrics (e.g., NDCG@k,  precision@k, BLEU, ROUGE) to demonstrate improved accuracy.
- Documentation: Clearly comment your code and provide instructions for replication.

Good luck! If you have any questions, please feel free to reach out to kairat@kodif.ai (cc: norm@kodif.ai) for clarifications.
