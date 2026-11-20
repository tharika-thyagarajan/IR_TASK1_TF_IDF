TF-IDF Based Information Retrieval System

This project implements a simple Information Retrieval (IR) system using TF-IDF (Term Frequency–Inverse Document Frequency) to identify and rank relevant documents based on user queries.

The system uses a collection of 10 text documents related to Artificial Intelligence and technology. It performs text preprocessing, including lowercasing, tokenization, stop-word removal, and stemming, followed by the construction of a Term-Document Matrix.

TF, DF, and IDF values are calculated to generate the TF-IDF matrix. Cosine similarity is then used to compare user queries with the documents and rank the results based on relevance.

Features

- Text preprocessing using NLTK
- Term-Document Matrix construction
- TF, DF, and IDF calculations
- TF-IDF matrix generation
- TF-IDF heatmap visualization
- Manual TF-IDF calculation
- Query processing and cosine similarity
- Document ranking and retrieval
- Unknown-term query testing
- Analysis of retrieval results

Technologies Used

Python, Google Colab, Pandas, NumPy, NLTK, Scikit-learn, Matplotlib, Seaborn

Course: Information Retrieval (21CSE377T)
Assignment: CLA2 – TF-IDF in Action: Build, Compute, Rank and Explain
