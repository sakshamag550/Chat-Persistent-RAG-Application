# 📚 MultiPDF Chat App

Interact with multiple PDF documents using natural language queries powered by AI.

## 🔍 Overview

The **MultiPDF Chat App** is a user-friendly application built with Streamlit that allows users to upload and query multiple PDFs simultaneously. Leveraging advanced language models and vector search, it provides intelligent, context-aware responses based on your documents.

![App Architecture](./docs/PDF-LangChain.jpg)

---

## 🚀 Features

- 📄 Upload and process multiple PDFs
- 🤖 Ask questions in natural language
- 🧠 Contextual chat powered by OpenAI or HuggingFace models
- 🔍 Semantic search through embedded vector databases (FAISS)
- 🧩 Real-time conversation memory

---

## ⚙️ How It Works

1. **PDF Loading**: Extracts text from all uploaded PDF pages.
2. **Text Chunking**: Breaks down large text into manageable chunks.
3. **Embedding**: Converts chunks into semantic vector representations.
4. **Similarity Matching**: Finds most relevant chunks for your query.
5. **Chat Generation**: Uses a language model to generate answers based on matched content.

---

## 🛠 Installation

### 1. Clone the Repository

```bash
git clone git@github.com:Abhiz2411/multipdf-chat-app.git
cd multipdf-chat-app
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Set Up Environment Variables

Create a `.env` file with your OpenAI API key:

```env
OPENAI_API_KEY=your_secret_api_key
```

---

## ▶️ Usage

Run the app with Streamlit:

```bash
streamlit run app.py
```

Once running:

1. Upload one or more PDF files via the sidebar.
2. Click **"Process"** to analyze documents.
3. Ask questions in the chat input field.

---

## 📁 Project Structure

```
├── app.py                 # Main application script
├── htmlTemplates.py       # Custom chat UI HTML templates
├── requirements.txt       # Python dependencies
├── .env                   # Environment variables (not included)
├── docs/
│   └── PDF-LangChain.jpg  # Architecture diagram
└── README.md
```

---

## 🧪 Models Supported

- **OpenAI GPT-4 / GPT-3.5**
- **HuggingFace Transformers (e.g., FLAN-T5, Instructor-XL)**

---

## 🪪 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## ✨ Acknowledgments

Inspired by educational content from [YouTube Tutorial](https://youtu.be/dXxQ0LR-3Hg) and built using LangChain, FAISS, and Streamlit.

---

## 🔖 Suggested Repository Name

**`multipdf-chat-app`** — clean, descriptive, and keyword-rich for discoverability.
