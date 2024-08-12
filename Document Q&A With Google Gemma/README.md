# Gemma Model Document Q&A

## Overview

This project is a Streamlit application that allows users to ask questions about documents using the Gemma Model. The app utilizes a combination of OpenAI's and Google Generative AI's models for document processing and Q&A. It supports document embedding and retrieval using FAISS vector stores, and processes PDF files stored in a specified directory.

## Features

- **Document Ingestion:** Loads and processes PDF documents from a specified directory.
- **Text Splitting:** Splits documents into manageable chunks for processing.
- **Vector Embedding:** Embeds documents into a vector store for efficient retrieval.
- **Q&A Interface:** Allows users to input questions and get answers based on the context of the documents.
- **Document Similarity Search:** Displays chunks of the document that are most similar to the user's query.

## Requirements

- Python 3.8+
- Streamlit
- LangChain
- FAISS
- PyPDF
- dotenv

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Venkata-Gopi-Personal-Projects/Gen-Ai-With-Google-Gemini-Projects.git
   cd Gen-Ai-With-Google-Gemini-Projects
   
2. **Install the required Python packages:**
   ```bash
   pip install -r requirements.txt
   
3. **Run the Streamlit app:
 ```bash
streamlit run your_script_name.py

