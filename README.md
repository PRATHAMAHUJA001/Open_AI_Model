ChatGPT Document QA with Instructor Embeddings

Overview

This repository contains an implementation of a ChatGPT-like model enhanced with Hugging Face instructor embeddings. The model is designed to answer questions based on uploaded documents, providing a convenient way to interactively retrieve information from a set of documents.

Features

Document Upload: Users can upload documents in various formats, including PDFs.
Document Question Answering: The model utilizes instructor embeddings from Hugging Face to enhance its understanding of the uploaded documents, enabling accurate and context-aware question answering.
Web Interface: The application is built using Streamlit, providing a user-friendly web interface for document uploading and question answering.
Installation

To install the required libraries, run:

bash
Copy code
pip install langchain PyPDF2 python-dotenv streamlit faiss-cpu altair tiktoken

Create a file named .env in the project root and add your Hugging Face API key:
plaintext
Copy code
HUGGINGFACE_API_KEY=your-api-key
You can obtain the API key by signing up on the Hugging Face website.
Usage

Run the Streamlit app:

streamalit run pp.py

Acknowledgments

This project makes use of the Hugging Face model embeddings for improved document understanding.
Special thanks to the contributors of the following libraries:
LangChain
PyPDF2
python-dotenv
Streamlit
faiss-cpu
Altair
Tiktoken
