# Retrievel Augmented Generation (RAG) For Resume and Work Portfolio Analysis

This project is aimed at creating a Retrieval Augmented (RAG) pipeline to enable users to ask questions from my Resume and Work Portfolio. The user can ask any question about my career - work experience, projects, academics, accomplishments, skills and more. 

In the attached notebook, we will follow three approaches to implement Retrieval Augmented Generation (RAG):
1. Basic RAG Pipeline:
    - Basic Indexing of Documents using LlamaIndex.
    - Querying from the Created Index.
  
![alt text](https://github.com/faizankhan29/RAG-For-Resume-and-Work-Portfolio-Analysis/blob/main/images/basic_1.png?raw=true)


Source:https://learn.deeplearning.ai/building-evaluating-advanced-rag/lesson/2/advanced-rag-pipeline



2. Advanced RAG Pipeline - Sentence Window Retrieval:
    - Creating Sentence Window Based Index (Breaks down documents into smaller chunks like sentences).
    - Querying most relevant chunks along with surrounding context.

![alt text](https://github.com/faizankhan29/RAG-For-Resume-and-Work-Portfolio-Analysis/blob/main/images/sentence_window_1.png?raw=true)

Source: https://learn.deeplearning.ai/building-evaluating-advanced-rag/lesson/2/advanced-rag-pipeline

![alt text](https://github.com/faizankhan29/RAG-For-Resume-and-Work-Portfolio-Analysis/blob/main/images/sentence_window_2.png?raw=true)


Source: https://learn.deeplearning.ai/building-evaluating-advanced-rag/lesson/2/advanced-rag-pipeline

3. Advanced RAG Pipeline - Auto-merging retrieval:
    - Creating Automerging Retrieval Based Index.
    - Querying using auto-merging retrieval which merges information from multiple sources or segments of text to create a more comprehensive and contextually relevant response to a query.
  
![alt text](https://github.com/faizankhan29/RAG-For-Resume-and-Work-Portfolio-Analysis/blob/main/images/am_retrieval.png?raw=true)

Source: https://learn.deeplearning.ai/building-evaluating-advanced-rag/lesson/2/advanced-rag-pipeline
