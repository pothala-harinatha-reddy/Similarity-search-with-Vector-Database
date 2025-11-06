# 🔍 Semantic Search using Sentence Transformers and FAISS

## 📘 Overview
This project demonstrates how to perform **semantic similarity search** on text using **Sentence Transformers** for embeddings and **FAISS** (Facebook AI Similarity Search) for efficient vector indexing and retrieval.  

Given a paragraph or document, the system:
1. Splits it into individual sentences  
2. Converts each sentence into vector embeddings  
3. Stores those vectors in a FAISS index  
4. Retrieves the top similar sentences based on a user’s query  

---

## 🧠 What This Project Does
- 🧩 Converts text into dense numerical **embeddings**
- ⚡ Uses **FAISS** for fast similarity search
- 🔍 Finds semantically similar sentences to a user query
- 🧾 Demonstrates end-to-end NLP workflow: preprocessing → embedding → indexing → search

---

## 🧰 Tech Stack
- **Python 3.x**
- **Sentence Transformers**
- **FAISS (Facebook AI Similarity Search)**
- **NumPy**
- **Regular Expressions (re)**
