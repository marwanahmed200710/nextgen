# 🩺 End-to-End Medical RAG & Evaluation Pipeline

A robust Retrieval-Augmented Generation (RAG) and evaluation framework designed to answer clinical hypertension questions using domain-specific medical guidelines.

## 📌 Features
* **PDF Parsing & Chunking**: Automatic document parsing with overlapping text chunking and section extraction.
* **Vector Search & Retrieval**: Dense retrieval using sentence-transformers and cosine similarity.
* **Local LLM Generation**: Powered by Qwen 3.5 (2B) running locally on GPU.
* **Reasoning Tag Filtering**: Built-in post-processing logic to strip Chain-of-Thought (<think> tags) and force concise, direct clinical answers.
* **RAG Evaluation Metrics**: Precision@3 and Hit Rate benchmarks exported to CSV.

## 🚀 Installation & Usage
pip install git+https://github.com/huggingface/transformers.git
pip install chromadb pandas rich json-repair pypdf sentence-transformers