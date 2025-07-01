# LangChain_Will
A lightweight LLM-powered tool to extract and summarize key information from long PDF wills using open-source models, FAISS for vector search, and HuggingFace Transformers. Ideal for legal assistants and researchers.

# Will Summarizer using LLMs 🧠📜

This project uses free, local large language models and vector databases to summarize lengthy legal documents—specifically wills (100+ pages)—by breaking them into chunks, indexing with FAISS, and querying relevant sections to generate concise summaries.

## 🔧 Features
- ✅ PDF to text parsing with intelligent chunking
- ✅ FAISS vector store for semantic search
- ✅ HuggingFace models (e.g., Flan-T5) for generation
- ✅ Open-source and local (no OpenAI key needed)
- ✅ Custom queries for legal exploration

## 📁 Steps
1. **Ingest PDF and split into semantic chunks**
2. **Embed with sentence transformers**
3. **Store/retrieve with FAISS**
4. **Generate summaries from relevant chunks**

## 📦 Models
- Embedding: `all-MiniLM-L6-v2`
- Generation: `google/flan-t5-base` (fully free)

## 💡 Example Usage
```bash
python step3_query_local.py
❓ Ask something about the will: Who gets the estate?
