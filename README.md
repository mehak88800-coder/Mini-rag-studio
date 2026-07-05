Here's a professional `README.md` for your **Mini_RAG_Studio** project.

# 🤖 Mini RAG Studio

A lightweight **Retrieval-Augmented Generation (RAG)** application that enables users to upload documents and ask questions using **Google Gemini**, **LangChain**, **FAISS**, **ChromaDB**, and **Hugging Face Embeddings** through an interactive **Streamlit** interface.

---

## 🚀 Features

* 📄 Upload and process PDF documents
* 🔍 Semantic search using vector embeddings
* 🤖 AI-powered question answering with Google Gemini
* 🧠 Retrieval-Augmented Generation (RAG)
* ⚡ Interactive Streamlit web application
* 📚 Automatic document chunking
* 💾 Vector database support with FAISS and ChromaDB

---

## 🛠️ Tech Stack

* Python
* Streamlit
* LangChain
* Google Gemini API
* Hugging Face Embeddings
* FAISS
* ChromaDB

---

## 📂 Project Structure

```text
Mini_RAG_Studio/
│── app.py
│── requirements.txt
│── .gitignore
│── data/
│── database/
│── utils/
│   ├── embeddings.py
│   ├── loader.py
│   ├── splitter.py
│   ├── vectorstore.py
│   └── rag_chain.py
│── test_embedding.py
│── test_loader.py
│── test_splitter.py
│── test_faiss.py
│── test_gemini.py
│── test_rag.py
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/mehak88800-coder/Mini-rag-studio.git
```

### Move into the project directory

```bash
cd Mini-rag-studio
```

### Create a virtual environment

```bash
python -m venv rag_env
```

### Activate the virtual environment

**Windows**

```bash
rag_env\Scripts\activate
```

**Linux/macOS**

```bash
source rag_env/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the project root.

```env
GOOGLE_API_KEY=YOUR_GEMINI_API_KEY
```

> **Note:** Never upload your `.env` file or API keys to GitHub.

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will automatically open in your browser.

---

## 💡 Example Questions

* Summarize the uploaded document.
* What are the key points?
* Explain the main topic.
* Give a short overview of the document.
* List the important concepts discussed.

---

## 📌 Future Enhancements

* Support for multiple document uploads
* Chat history
* Conversation memory
* Citation-aware responses
* Hybrid search (keyword + semantic)
* Deployment on Streamlit Community Cloud

---

## 👩‍💻 Author

**Mehak**

GitHub: [https://github.com/mehak88800-coder](https://github.com/mehak88800-coder)

---

## 📄 License

This project is intended for educational and learning purposes.

You can further improve the repository by adding screenshots of the Streamlit interface and a `requirements.txt` containing all required dependencies so others can run the project easily.
