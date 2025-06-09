# 📄 PDF Q&A System using FAISS & Google Gemini

This project demonstrates a lightweight document-based Q&A system built in Google Colab. It allows users to upload a PDF, embed its contents into a vector database (FAISS), and query it using Google Gemini's Generative AI API.

---

## 🚀 Features

- ✅ Upload and read PDF using PyMuPDF
- ✅ Chunk and embed text using Sentence Transformers
- ✅ Store embeddings in a FAISS vector database
- ✅ Search and retrieve relevant text chunks
- ✅ Query using Gemini API with context-based answers

---

## 🛠 Tech Stack

- Python
- [LangChain](https://www.langchain.com/)
- [Sentence Transformers](https://www.sbert.net/)
- [FAISS](https://github.com/facebookresearch/faiss)
- [Google Generative AI (Gemini)](https://ai.google.dev/)
- PyMuPDF

---

## 🧪 How It Works

1. Upload a PDF or provide its path.
2. Extract the text using `PyMuPDF`.
3. Split the text into overlapping chunks.
4. Convert those chunks into embeddings using `Sentence Transformers`.
5. Store embeddings in a local `FAISS` database.
6. On user input, retrieve the most relevant chunks using vector similarity.
7. Feed those chunks and the user’s question to Gemini API to generate a contextual answer.

---

## 📦 Installation

Install the required Python packages:

```bash
pip install -U langchain langchain-community faiss-cpu sentence-transformers google-generativeai pymupdf
