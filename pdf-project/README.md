# Chat with PDF

An interactive PDF document analysis tool that allows users to upload PDFs and engage in multilingual conversations about their content.

## Features

- 📚 Upload and process multiple PDF documents
- 💬 Interactive chat interface for document queries
- 🌐 Multilingual support with auto-language detection
- 🔄 Automatic translation capabilities
- 💾 Persistent storage of processed documents
- 🧠 Context-aware conversation memory

## Requirements

- Python 3.8+
- Groq API Key
- Google API Key

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd pdf-project
```

2. Install required packages:
```bash
pip install -r requirements.txt
```



## Usage

1. Run the Streamlit app:
```bash
streamlit run src/app.py
```

2. Open your web browser and navigate to the provided URL (typically http://localhost:8501)

3. Enter your API keys in the sidebar

4. Upload PDF documents and click "Process Documents"

5. Start asking questions about your documents!

## Language Support

- Automatic detection of document languages
- Support for 100+ languages
- Auto-translation capabilities
- Option to force responses in specific languages

## Project Structure

```
pdf-project/
├── src/
│   └── app.py
├── requirements.txt
├── .env
└── README.md
```

## Dependencies

- streamlit
- langchain-groq
- langchain
- langchain-core
- langchain-community
- langchain-google-genai
- faiss-cpu
- pypdf
- python-dotenv
- pycountry
- langdetect
- deep-translator

