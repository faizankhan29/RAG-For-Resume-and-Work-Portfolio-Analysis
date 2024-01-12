# Retrievel Augmented Generation (RAG) For Resume and Work Portfolio Analysis

This project is aimed at creating a Retrieval Augmented (RAG) pipeline to enable users to ask questions from my Resume and Work Portfolio. The user can ask any question about my career - work experience, projects, academics, accomplishments, skills and more. 

In the attached notebook, we will follow three approaches to implement Retrieval Augmented Generation (RAG):
1. Basic RAG Pipeline:
    - Basic Indexing of Documents using LlamaIndex.
    - Querying from the Created Index.

2. Advanced RAG Pipeline - Sentence Window Retrieval:
    - Creating Sentence Window Based Index (Breaks down documents into smaller chunks like sentences).
    - Querying most relevant chunks along with surrounding context.

3. Advanced RAG Pipeline - Auto-merging retrieval:
    - Creating Automerging Retrieval Based Index.
    - Querying using auto-merging retrieval which merges information from multiple sources or segments of text to create a more comprehensive and contextually relevant response to a query.