

## 📝 **README.md (for GitHub)**

````markdown
# 🧠 RAG Document Q&A with Groq and Llama 3.1

A simple and powerful Retrieval-Augmented Generation (RAG) application that allows users to query research papers and get precise answers using **Groq Llama 3.1** and **FAISS vector search**.

---

## 🚀 Features

- Upload multiple research papers (PDFs)
- Generate vector embeddings using **HuggingFace MiniLM**
- Query documents using **Groq Llama 3.1-8B Instant**
- Context-aware answers with source document references
- Interactive Streamlit interface

---

## 🧩 Tech Stack

- **Python 3.10+**
- **LangChain**
- **Groq API**
- **FAISS** (for vector search)
- **Streamlit** (for web app)
- **HuggingFace Embeddings**

---

## ⚙️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/RAG-Document-QA.git
   cd RAG-Document-QA
````

2. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   venv\Scripts\activate     # On Windows
   source venv/bin/activate  # On macOS/Linux
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Create a `.env` file in the root directory:

   ```
   GROQ_API_KEY=your_groq_api_key
   HF_TOKEN=your_huggingface_token
   OPENAI_API_KEY=optional_if_any
   ```

5. Add your PDF documents inside the `research_papers/` folder.

---

## ▶️ Run the App

```bash
streamlit run main.py
```

Once running, open the local URL displayed in the terminal.

---

## 📚 Example Usage

1. Click **“Create Document Embedding”**
2. Type your question about the uploaded research papers
3. View the generated answer and related document snippets

---

## 📦 Folder Notes

* `main.py` — Streamlit interface and RAG pipeline
* `requirements.txt` — dependencies
* `research_papers/` — folder for PDF inputs
* `.env` — private API keys (don’t upload to GitHub)

---

## 🤖 Model Information

* **Embedding model:** `all-MiniLM-L6-v2`
* **LLM model:** `llama-3.1-8b-instant` (Groq)

---

## 💡 Future Enhancements

* Support for DOCX and TXT files
* Multiple LLM backend options
* Improved context ranking and summarization

---

## 🧑‍💻 Author

**Bharath Kumar Reddy**
RAG | LLM | LangChain | Groq | Streamlit | AI Applications

````

---

## ⚙️ **Commands to Push to GitHub**

1. Initialize a Git repo
   ```bash
   git init
````

2. Add all project files

   ```bash
   git add .
   ```

3. Commit changes

   ```bash
   git commit -m "Initial commit - RAG Document Q&A with Groq and Llama 3.1"
   ```

4. Create a GitHub repository
   (example name: `RAG-Document-QA`)

5. Link remote repo

   ```bash
   git remote add origin https://github.com/<your-username>/RAG-Document-QA.git
   ```

6. Push your project

   ```bash
   git branch -M main
   git push -u origin main
   ```

---

