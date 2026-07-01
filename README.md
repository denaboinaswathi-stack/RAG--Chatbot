# 📚 RAG Chatbot using LangChain & Ollama

A Retrieval-Augmented Generation (RAG) chatbot that enables users to chat with PDF documents using Large Language Models (LLMs). The application retrieves relevant information from uploaded documents and generates accurate responses in real time.

---

## ✨ Highlights

- 📄 Upload and analyze PDF files
- 🔍 Semantic search with vector embeddings
- 🤖 AI-powered question answering
- ⚡ Fast document retrieval using ChromaDB
- 🌐 Interactive Streamlit interface
- 🧠 Powered by LangChain and Ollama

---

## 🏗️ Built With

- Python
- Streamlit
- LangChain
- ChromaDB
- Hugging Face Embeddings
- Ollama (Llama 3)

---

## 📁 Project Structure

```
RAG-Chatbot/
├── app.py
├── requirements.txt
├── README.md
├── data/
└── chroma_db/
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/RAG-Chatbot.git
cd RAG-Chatbot
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Install and run Ollama:

```bash
ollama pull llama3
ollama serve
```

Start the application:

```bash
streamlit run app.py
```

---

## 🚀 Usage

1. Launch the application.
2. Upload a PDF document.
3. Wait for the document to be indexed.
4. Ask questions related to the uploaded content.
5. Receive context-aware AI-generated responses.

---

## 🧠 How It Works

- PDF documents are loaded and split into smaller chunks.
- Text chunks are converted into embeddings using Hugging Face models.
- Embeddings are stored in ChromaDB for efficient retrieval.
- Relevant chunks are fetched based on the user's question.
- Ollama's Llama 3 model generates an answer using the retrieved context.

---

## 📌 Future Enhancements

- Multiple document support
- Chat history
- Source references
- Voice input
- Document summarization
- User authentication
- Cloud deployment

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository, create a feature branch, and submit a pull request.

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.

---

## 📄 License

This project is licensed under the MIT License.
