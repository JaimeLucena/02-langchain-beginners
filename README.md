# 02-langchain-beginners

> **A comprehensive, hands-on guide to mastering LangChain fundamentals through practical Jupyter notebooks.**

This repository is the second module in a progressive learning series on Generative AI and LangChain, designed to take you from basic concepts to building production-ready RAG (Retrieval-Augmented Generation) systems.

---

## 📚 Overview

This course provides a structured, step-by-step introduction to **LangChain** using modern patterns and tools:

- **Progressive Learning**: 15 notebooks covering everything from prompt templates to vector stores
- **Modern Stack**: Built with LCEL (LangChain Expression Language), OpenAI, FAISS, Chroma
- **Practical Examples**: Each concept includes working code and real-world applications
- **Production-Ready**: Learn patterns used in professional LLM applications

Perfect for developers, data scientists, and AI enthusiasts who want to build robust LLM-powered applications.

---

## 📚 Course Structure

| Notebook | Topic | Description |
|-----------|--------|-------------|
| `00` | **API Keys & Environment Setup** | Secure management of credentials and configuration |
| `01` | **Fundamentals Concepts** | Core LLM ideas: context, tokens, prompts, hallucinations |
| `02` | **LLM App Architecture** | Understanding how LLM-based applications are structured |
| `03` | **Load Env & Basic Model** | Load environment variables and call OpenAI / Groq models |
| `04` | **Prompt Templates** | Build and format prompts with `PromptTemplate` and `ChatPromptTemplate` |
| `05` | **Chains** | What is a chain? Build your first LCEL pipeline |
| `06` | **Chain Types** | Explore `RunnablePassthrough`, `RunnableLambda`, and `RunnableParallel` |
| `07` | **Built-in Functions** | Using `.bind()`, `.bind_tools()`, and `.assign()` for modular logic |
| `08` | **Composing Chains** | Nested and dependent chains (fan-out / fan-in) |
| `09` | **RAG Introduction** | Conceptual introduction to Retrieval-Augmented Generation |
| `10` | **Data Loaders** | Loading data with LangChain’s community loaders |
| `11` | **Text Splitters** | Chunking large documents with `RecursiveCharacterTextSplitter` |
| `12` | **Text Embeddings** | Converting text into vector embeddings |
| `13` | **Vector Stores** | Storing and querying embeddings with Chroma or FAISS |
| `14` | **VectorStore Retriever** | Using vector stores as retrievers for semantic search |

---

## 🚀 Getting Started

### Prerequisites

- **Python**: 3.10, 3.11, or 3.12
- **uv**: Fast Python package installer ([install guide](https://github.com/astral-sh/uv))
- **OpenAI API Key**: Required for running examples ([get one here](https://platform.openai.com/api-keys))

### Installation

1. **Clone the repository**:
```bash
   git clone https://github.com/JaimeLucena/02-langchain-beginners.git
   cd 02-langchain-beginners
```

2. **Install dependencies**:
```bash
   uv sync
```

3. **Set up environment variables**:
   
   Create a `.env` file in the root directory:
```env
   OPENAI_API_KEY=your_openai_api_key_here
   GROQ_API_KEY=your_groq_api_key_here  # Optional
```

4. **Launch Jupyter**:
```bash
   uv run jupyter lab
```

5. **Start with notebook `00`** and work through them sequentially.

---

## 🛠️ Technology Stack

- **LangChain Core**: `>=0.3.0` (modern LCEL patterns)
- **LLM Providers**: OpenAI, Groq (optional OSS models)
- **Vector Databases**: FAISS, ChromaDB
- **Data Processing**: LangChain text splitters and community loaders

---

## 📖 Learning Path

### Phase 1: Foundations (Notebooks 00-04)
Learn the basics of prompts, templates, and environment management.

### Phase 2: Chains & Composition (Notebooks 05-08)
Master LCEL chains, parallel execution, and advanced composition patterns.

### Phase 3: RAG Systems (Notebooks 09-14)
Build complete retrieval-augmented generation pipelines with vector stores.

---

## 🎯 What You'll Build

By the end of this course, you'll be able to:

- ✅ Create dynamic prompt templates with ChatPromptTemplate
- ✅ Build and compose LCEL chains for complex workflows
- ✅ Implement RAG systems with semantic search
- ✅ Use vector stores (FAISS/Chroma) for efficient document retrieval
- ✅ Structure production-ready LLM applications
- ✅ Apply modern LangChain patterns and best practices

---

## 📋 Prerequisites Knowledge

This is the **second course** in the series. You should be comfortable with:

- Python fundamentals (covered in [01-python-fundamentals](https://github.com/JaimeLucena/01-python-fundamentals))
- Basic understanding of APIs and JSON
- Familiarity with Jupyter notebooks

No prior LLM or LangChain experience required!

---

## 🤝 Contributing

Found a bug or have a suggestion? Contributions are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new example'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🔗 Related Resources

- [LangChain Documentation](https://docs.langchain.com/)  
- [LangChain Python API Reference](https://reference.langchain.com/python/)  
- [LangGraph Documentation](https://langchain-ai.github.io/langgraph/)  
- [OpenAI API Reference](https://platform.openai.com/docs/) 

---

## 👨‍💻 Author

**Jaime Lucena**

- GitHub: [@JaimeLucena](https://github.com/JaimeLucena)

---

## ⭐ Support

If you find this course helpful, please consider giving it a star! ⭐

---

**Ready to master LangChain?** Start with [notebook 00](notebooks/00_api_keys_and_env_vars.ipynb) and begin your journey! 🚀