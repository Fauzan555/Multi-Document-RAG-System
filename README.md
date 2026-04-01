# 🚀 Project Overview

The Multi-Document Retrieval-Augmented Generation (RAG) System is an AI-powered tool that allows users to ask questions over multiple PDF documents and receive precise, context-aware answers. This system combines document processing, text embedding, and vector similarity search to enable interactive querying on large datasets.

This project demonstrates my expertise in:

Natural Language Processing (NLP) and embeddings
Document handling and chunking
Building vector databases using Chroma
Querying and retrieving information using a RAG pipeline
# 🛠 Key Features
# 1 PDF Document Ingestion
Supports single PDF files or entire folders.
Automatically loads, parses, and splits text into manageable chunks for embedding.
# 2 Vector Database Creation (Chroma)
Converts text chunks into embeddings using sentence-transformers/all-MiniLM-L6-v2.
Stores embeddings in a persistent Chroma collection for efficient similarity search.
# 3 Interactive Q&A
Users can ask questions interactively.
Returns precise answers based on the content of uploaded PDFs.
Handles multiple queries with fast retrieval from the vector store.
# 4 Metadata Tracking
Each text chunk retains metadata about its source PDF.
Ensures traceability and context-aware responses.
# 5 Extensible & Modular
Easy to integrate new embedding models or document loaders.
Functions like load_documents, split_text, and create_vector_store are modular and reusable.

# 📝 Usage

Run the system:

python main.py
When prompted, enter your query.
Type exit to close the program.

Example:

❓ Ask a question (or type 'exit'): Who is the author of the document?
🧠 Answer: ACE-PREP
# 💡 Technologies Used

NLP / Embeddings	sentence-transformers (MiniLM-L6-v2)
Vector Database	chromadb
Document Handling	PyPDFLoader (LangChain community)
Python Libraries	os, tqdm, langchain, numpy, pandas
IDE / Notebook	Jupyter Notebook
