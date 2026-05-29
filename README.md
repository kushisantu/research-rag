# Research Paper Q&A (RAG)

Ask questions about any research paper and get cited answers back.

## Architecture
- PDF ingestion + chunking via LangChain
- Embeddings stored in ChromaDB (local) / Pinecone (cloud)
- Retrieval chain with Gemini as the LLM backbone
- FastAPI backend, React frontend
- Deployed on AWS Lambda

## Tech Stack
LangChain · ChromaDB · Gemini API · FastAPI · React · AWS Lambda
