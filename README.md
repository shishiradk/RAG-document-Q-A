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

---

![Screenshot 2025-07-03 084201](https://github.com/user-attachments/assets/d9ce8d92-0b20-4870-870f-c3fb1f9b9b80)

---

![Screenshot 2025-07-03 084319](https://github.com/user-attachments/assets/d328f49b-714b-4819-a3fb-391c88d3c2b0)

---

![Screenshot 2025-07-03 084331](https://github.com/user-attachments/assets/63fbd72e-b1bf-43cb-9d32-beb3accc2d06)

---

![Screenshot 2025-07-03 084344](https://github.com/user-attachments/assets/313291ba-cca5-45ea-9e72-0a60f317808c)

---





