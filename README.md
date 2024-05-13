# Pandemic-COVID-19--Based-IR-System

COVID-19 Information Retrieval System
Overview
This project develops an information retrieval system tailored for the COVID-19 Open Research Dataset (CORD-19). The system utilizes a BERT model to generate vector embeddings for documents and queries, enabling the retrieval of the most relevant documents based on cosine similarity scores. This tool is designed to assist researchers and medical professionals by providing quick and efficient access to the most relevant COVID-19 related research papers.

Features
BERT Embeddings: Leverage BERT model for generating high-quality vector embeddings of the textual data.
Cosine Similarity Scoring: Utilize cosine similarity to rank documents based on their relevance to a user query.
Preprocessing: Implements preprocessing steps on the CORD-19 dataset to optimize the text data for better model performance.
Top-N Retrieval: Retrieves and displays the top N documents that best match the user's search query.
Dataset
The CORD-19 dataset is a resource of over 280,000 scholarly articles, including over 150,000 with full text, about COVID-19.
Dataset link: https://www.kaggle.com/datasets/allen-institute-for-ai/CORD-19-research-challenge

Technology Stack
Python: Primary programming language.
Transformers by Hugging Face: For utilizing pretrained BERT models.
NumPy: For handling large, multi-dimensional arrays and matrices.
Scikit-learn: For cosine similarity computation and other machine learning utilities.
