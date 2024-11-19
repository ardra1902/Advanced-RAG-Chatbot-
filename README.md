
# Chat with Doc 📄

This application allows users to upload a PDF document and interact with it through a conversational interface using a state-of-the-art language model, Llama-3.1-70b. The app leverages LangChain for building conversational AI pipelines, HuggingFace embeddings for text encoding, and FAISS for efficient vector search.



## Features

-PDF Upload: Upload a PDF document for processing.

-Document Parsing: Extract and split the document into manageable chunks for embedding.

-Embeddings: Use HuggingFace for document chunk vectorization.

-Retrieval-augmented Generation (RAG): Perform conversational queries with contextual memory, backed by FAISS vector search.

-Conversational Interface: Maintain a conversation history for seamless interaction.

### Installation


**Clone the repository:**
   ```bash
   git clone https://github.com/ardra1902/Advanced-RAG-Chatbot-
   cd Advanced-RAG-Chatbot-
```


## Tech Stack

-Python

-Streamlit: For creating the web-based user interface.

-LangChain: For building conversational AI chains.

-HuggingFace Embeddings: For text embedding generation.

-FAISS: For vector search and retrieval.

-ChatGroq (Llama-3.1-70b): For large language model interactions.

-dotenv: For environment variable management.




## How It Works

How It Works
PDF Parsing:

Uploaded PDFs are processed with PyPDFLoader to extract text content.
Text Splitting:

The document is split into smaller chunks using LangChain's CharacterTextSplitter.
Embedding and Vector Search:

Each text chunk is converted into a vector using HuggingFace embeddings.
FAISS is used to index and retrieve relevant chunks.
Conversation Chain:

A conversational retrieval chain is created using the Llama-3.1-70b model and a conversation buffer memory to handle context.
Interactive Chat:

Users interact with the document through the Streamlit chat interface.
## Contributions

Contributions are welcome! Please fork the repository and create a pull request with your feature additions or bug fixes.
## Feedback


If you have any feedback, please reach out to me at ardrakakkarath@gmail.com

Feel free to star ⭐ this repository if you find it helpful!
