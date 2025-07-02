# RAG-document-Q-A

A Streamlit app for Question Answering (Q&A) over research papers using Retrieval-Augmented Generation (RAG) and Groq LLMs.

---

## Features

- Loads PDFs from `research_papers/`
- Splits documents for efficient retrieval
- Uses Ollama embeddings + FAISS for vector search
- Answers questions using Groq LLM (`Qwen-Qwq-32b`)
- Simple Streamlit interface

---

## Setup

1. **Clone the repo:**
   ```sh
   git clone https://github.com/yourusername/RAG-document-Q-A.git
   cd RAG-document-Q-A

---

### Install dependencies:
pip install -r requirements.txt

---

### Set environment variables:
OPENAI_API_KEY=your_openai_api_key
GROQ_API_KEY=your_groq_api_key

---

### Add PDFs:
Place your research papers in the research_papers/ folder.

---

### Run
streamlit run [app.py](http://_vscodecontentref_/0)

---

### Usage
Click Document Embedding to process PDFs.
Enter your question.
View answers and relevant document excerpts.


---

### License
MIT License ``

