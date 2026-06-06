# 📄 Research Paper Summarization Application

An NLP-powered web application that automatically summarizes uploaded PDF documents using a transformer-based language model. Built with **Streamlit**, **LangChain**, and **Hugging Face Transformers**, this tool helps users quickly understand long research papers and documents.

---

## 🚀 Features

- 📂 Upload PDF documents directly in the web app
- 🧠 Automatic abstractive summarization using **LaMini-Flan-T5-248M**
- 📑 Efficient document chunking for handling long texts
- 👀 встро PDF viewer for document preview
- ⚡ Real-time summary generation
- 🖥️ Simple and interactive Streamlit interface

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit** – Web UI
- **LangChain** – Document loading & text splitting
- **Hugging Face Transformers** – NLP model pipeline
- **PyTorch** – Model backend
- **LaMini-Flan-T5-248M** – Pretrained summarization model

---

## 🧠 How It Works

1. User uploads a PDF file via the Streamlit interface  
2. The PDF is loaded using `PyPDFLoader`  
3. Text is split into smaller chunks using `RecursiveCharacterTextSplitter`  
4. All chunks are combined and passed into a Hugging Face summarization pipeline  
5. The **LaMini-Flan-T5-248M** model generates a concise summary  
6. The summary is displayed alongside the uploaded document

---

## 📦 Installation

### 1. Clone the repository
```bash
git clone https://github.com/your-username/research-paper-summarizer.git
cd research-paper-summarizer
