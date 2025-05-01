# LangChain Chatbot with HuggingFace Embeddings

This is a simple document-based **Insurance Chatbot** built using [LangChain](https://www.langchain.com/), [HuggingFace Embeddings](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2), and PDF support via `PyPDFLoader`. The chatbot processes insurance-related documents (such as policy PDFs, terms & conditions, claim procedures, etc.) and can answer questions based on their content in a natural and intelligent manner.

---

## 🚀 Features

- Load insurance policy documents in PDF format
- Generate sentence embeddings with `HuggingFace Embeddings`
- Ask context-aware questions such as:
  - “What does this policy cover?”
  - “What is the claim procedure?”
  - “What are the exclusions in this plan?”

---

## 🧠 Tech Stack

- Python 3.10+
- LangChain
- HuggingFace Transformers + Sentence Transformers
- FAISS for vector storage
- Streamlit or Flask for UI (customizable)
