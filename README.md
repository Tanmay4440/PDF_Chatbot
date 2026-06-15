# 📚 PDF Chatbot

A Streamlit-based PDF Question Answering application that allows users to upload PDF documents and chat with them using Google's Gemini AI.

## Features

- Upload one or multiple PDF files
- Extract text from PDFs
- Create semantic search using FAISS
- Generate embeddings using Hugging Face Sentence Transformers
- Ask natural language questions about uploaded PDFs
- Conversation history tracking
- Export conversation history as CSV
- Modern chat-style interface
- Gemini 2.5 Flash integration

## Tech Stack

- Python
- Streamlit
- LangChain
- FAISS
- Hugging Face Embeddings
- Google Gemini API
- PyPDF2

## Installation

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/PDF_Chatbot.git
cd PDF_Chatbot
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

Linux / Mac:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## Run Application

```bash
streamlit run app.py
```

## Usage

1. Get a Gemini API Key from:
   https://ai.google.dev

2. Enter your API key in the sidebar.

3. Upload one or more PDF files.

4. Click **Submit & Process**.

5. Ask questions about the uploaded documents.


## Example Questions

- What is AQI?
- Summarize this document.
- What are the key findings?
- List the important points discussed.

## Future Improvements

- Source citations
- PDF page references
- Chat memory
- Multi-model support
- Document comparison
- Deployment on Streamlit Cloud

## Author

Tanmay Gaurav
