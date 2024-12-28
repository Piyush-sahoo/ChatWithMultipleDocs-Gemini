# Chat with PDF using Gemini

This application allows users to upload PDF files and interact with their content through a conversational AI interface. Leveraging Google Generative AI and FAISS for vector search, the app provides detailed and context-aware answers to user queries based on the uploaded PDFs.

## Features

- **PDF Text Extraction**: Extracts text content from uploaded PDF files.
- **Text Chunking**: Splits the text into manageable chunks for efficient processing.
- **Vector Search**: Uses FAISS to create and query vector embeddings for context-based retrieval.
- **Conversational AI**: Employs Google Generative AI for generating accurate, context-driven answers.

## Technologies Used

- **Streamlit**: For building the user interface.
- **Google Generative AI**: For embeddings and conversational responses.
- **FAISS**: For vector database creation and similarity search.
- **PyPDF2**: For PDF text extraction.
- **LangChain**: For chaining the question-answering process.

---

## Installation

### Prerequisites

- Python 3.8 or later installed on your system.
- A Google API key for using Google Generative AI.

### Steps

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
