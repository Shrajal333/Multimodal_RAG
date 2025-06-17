## Multimodal_RAG

Multimodal RAG is an end-to-end implementation of a Retrieval-Augmented Generation (RAG) pipeline that supports multimodal document processing. This notebook demonstrates how to parse PDFs, extract structured content (including text and images), and prepare inputs for large language models.

### 📌 Features
✅ Parses and chunks PDFs using unstructured
✅ Extracts both text and images using high-resolution strategies
✅ Embeds documents using OpenAI Embeddings API
✅ Stores and queries chunks via FAISS vector index
✅ Supports RAG-style question answering using OpenAI's GPT models
✅ Interactive querying for factual answers from parsed documents
