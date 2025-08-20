# RAG-from-Scratch-Building-Retrieval-Augmented-Generation-Step-by-Step
This repository provides a complete, from-scratch implementation of Retrieval-Augmented Generation (RAG) — a powerful approach that combines information retrieval with large language models for more accurate, factual, and context-aware responses.

## The project walks through:

🧾 Understanding the RAG architecture and its components (retriever + generator).

📂 Document preprocessing, chunking, and vectorization using embeddings.

🔍 Implementing a retriever with FAISS/Chroma for semantic search.

🧠 Integrating the retriever with a transformer-based generator (e.g., GPT, BERT, or similar).

⚙️ Building a query → retrieve → generate pipeline from scratch.

🧪 Running experiments, fine-tuning, and evaluating performance.

## Requirements

To run the models, we will use Ollama, a command-line tool that lets you run Hugging Face models locally. With Ollama, there’s no need for a server or cloud service—models can be executed directly on your computer.

### Download Ollama: https://ollama.com/

### After Ollama Installation run following in your commandline:

`ollama pull hf.co/CompendiumLabs/bge-base-en-v1.5-gguf`

`ollama pull hf.co/bartowski/Llama-3.2-1B-Instruct-GGUF`

### Install the ollama package:

`pip install ollama`




This repo is ideal for students, researchers, and practitioners who want to deeply understand and implement RAG without relying on heavy frameworks.

