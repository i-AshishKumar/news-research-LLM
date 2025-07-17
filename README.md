# 🧠 News Research LLM Tool

A lightweight, browser-based application that helps you analyze and extract insights from multiple news articles using LLMs and Retrieval-Augmented Generation (RAG). Just input a news URLs, ask a question, and get a grounded answer—with source links.

👉 [Live Demo](https://news-research-llm.streamlit.app/)

---

## 🚀 Features

- **Load URLs or Upload Files**  
  Paste article URLs directly, or upload a text file containing multiple links. The tool automatically fetches and processes each article.

- **Content Processing with LangChain**  
  Uses LangChain’s `UnstructuredURLLoader` to extract clean text content from news pages.

- **Vector Search with OpenAI + FAISS**  
  Converts article content into embeddings using OpenAI, and stores them in a FAISS index for fast semantic retrieval.

- **Question Answering with Source Attribution**  
  Ask natural-language questions and get LLM-generated answers that cite the specific URLs used for context.

---

## 🔧 How It Works (Tech Stack)

- **Frontend**: [Streamlit](https://streamlit.io/) for a clean, interactive UI  
- **Backend**:
  - **LangChain** for document loading, processing, and QA chaining
  - **OpenAI Embeddings** for semantic understanding of articles
  - **FAISS** for vector-based similarity search
  - **RetrievalQAWithSourcesChain** to generate answers grounded in source content

---

## 📦 Use Cases

- Equity and market research  
- Academic research or journalism  
- Competitive analysis or business intelligence  
- Anyone needing summarized insight from multiple sources

---

## 🧪 Try It

Go to the [live app](https://news-research-llm.streamlit.app/), drop in some news URLs, and start asking questions.

---

## 🛠️ Future Enhancements (Ideas)

- Add support for PDFs and other content types  
- Plug in Cohere/Anthropic models as drop-in LLM alternatives  
- Enable real-time scraping and auto-refresh of content  
- Multi-pass summarization or chain-of-thought QA

---

## 📄 License

MIT License  
