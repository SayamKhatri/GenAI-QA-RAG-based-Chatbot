# GenAI-QA-RAG-based-Chatbot

A Retrieval-Augmented Generation (RAG) chatbot that leverages LangChain, OpenAI's GPT models, and FAISS vector store to provide accurate and context-aware responses based on user uploaded documents.

## Overview
This project demonstrates how to build a question-answering chatbot that can ingest various document formats (PDF, DOCX, TXT, CSV), process them into vector embeddings, and utilize a language model to answer queries based on the content of these documents.

## Features

 **Document Ingestion**: Upload and process documents in PDF, DOCX, TXT, or CSV format.
 **Vector Store**: Utilize FAISS for efficient similarity search over document embedding.
 **Language Model Integration**: Employ OpenAI's GPT models via LangChain for generating response.
 **Interactive Interface**: Engage with the chatbot through a user-friendly Streamlit interfac.

## Project Structure

```
GenAI-QA-RAG-based-Chatbot/
├── RAG_Script.ipynb       # Jupyter Notebook demonstrating the RAG pipeline
├── README.md              # Project documentation
├── .gitignore             # Git ignore file
└── LICENSE                # MIT Licese
```


## Getting Started

### Prerequisites
- Python 3.8 or hiher
- OpenAI APIkey

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/SayamKhatri/GenAI-QA-RAG-based-Chatbot.git
   cd GenAI-QA-RAG-based-Chatbot
   ```


2. **Create and activate a virtual environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```


3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```


4. **Set your OpenAI API key:**

   ```bash
   export OPENAI_API_KEY='your-api-key'  # On Windows: set OPENAI_API_KEY='your-api-key'
   ```


5. **Run the Streamlit app:**

   ```bash
   streamlit run app.py
   ```

## Demo

<img width="1419" alt="Screenshot 2025-02-10 at 6 20 36 PM" src="https://github.com/user-attachments/assets/b5babd79-059b-4c09-9289-031eccb25d2b" />


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

