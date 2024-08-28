# Building and Deploying LLM Assistants in Cloud

This application implements a GPU-accelerated Retrieval-Augmented Generation (RAG) based Question-Answering system using NVIDIA Inference Microservices (NIMs) and the LlamaIndex framework. It allows users to upload documents, process them, and then ask questions about the content.

## Features

- Document loading and processing
- Vector storage and retrieval using Milvus
- Question-answering capabilities using NIMs
- Interactive chat interface built with Gradio

## How It Works

1. **Document Loading**: Users can upload multiple document files through the Gradio interface.

2. **Document Processing**: The application uses LlamaIndex to read and process the uploaded documents, splitting them into chunks.

3. **Embedding and Indexing**: The processed documents are embedded using NVIDIA's embedding model and stored in a Milvus vector database.

4. **Question Answering**: Users can ask questions through the chat interface. The application uses NIM with Llama 3 70B Instruct hosted on cloud to generate responses based on the relevant information retrieved from the indexed documents.

## I'll share more details in an article and provide the link here.
