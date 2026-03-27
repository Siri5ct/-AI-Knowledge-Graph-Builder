# 📄 AI Knowledge Graph Builder – Intelligent Query System

![Python](https://img.shields.io/badge/Python-3.11-blue)
![AI](https://img.shields.io/badge/AI-RAG%20Pipeline-green)
![Streamlit](https://img.shields.io/badge/UI-Streamlit-red)

Developed as part of Internship / AI Project  
Author: **Yashasree**

---

# 📖 Project Overview

The AI Knowledge Graph Builder is an intelligent system designed to process unstructured text data and transform it into a searchable knowledge base.

The system uses Natural Language Processing (NLP) techniques along with a Retrieval-Augmented Generation (RAG) pipeline to allow users to ask questions and retrieve relevant information from a dataset of customer complaints.

It converts textual data into embeddings, stores them using a vector database, and performs similarity-based retrieval to generate meaningful responses.

This project demonstrates how modern AI systems can efficiently handle large volumes of unstructured data and provide real-time answers.

---

# 🎯 Objective

The goal of this project is to:

- Process and clean unstructured text data  
- Convert text into vector embeddings  
- Store embeddings for efficient retrieval  
- Implement a semantic search system  
- Build a question-answering interface  
- Provide fast and relevant responses  

---

# 🏗 Project Architecture

Dataset (.pkl)
      ↓
Data Loading & Cleaning
      ↓
Text Embedding (Sentence Transformers)
      ↓
Vector Storage (FAISS)
      ↓
User Query
      ↓
Query Embedding
      ↓
Similarity Search
      ↓
Retrieve Relevant Data
      ↓
Answer Generation

---

# 🚀 Technologies Used

- Python – Core programming language  
- Streamlit – Web interface  
- Sentence Transformers – Text embeddings  
- FAISS – Vector similarity search  
- Pickle – Dataset storage  
- NumPy – Numerical operations  
- Visual Studio Code – Development  
- GitHub – Version control  

---

# 📦 Key Libraries Used

- streamlit  
- sentence-transformers  
- faiss-cpu  
- numpy  
- pickle  

---

# ✅ Milestone 1 – Data Processing

Tasks Completed:
- Loaded dataset from .pkl file  
- Cleaned text (removed placeholders like {product_purchased})  
- Converted raw data into usable format  

Output:
Clean and structured text data ready for embedding.

---

# ✅ Milestone 2 – Knowledge Graph Setup

Objective:
Build a structured representation of extracted data.

Tasks Completed:
- Extracted entities and relationships from text  
- Stored relationships in Neo4j graph database  
- Created nodes and edges representing real-world connections  

Output:
Basic knowledge graph representing relationships between entities.

---

# ✅ Milestone 3 – RAG System Implementation

Objective:
Enable semantic search and intelligent retrieval.

Steps:
- Converted text into embeddings using Sentence Transformers  
- Stored embeddings in FAISS  
- Processed user queries  
- Retrieved similar text using vector search  
- Generated answers from retrieved data  

Flow:
User Query → Embedding → FAISS Search → Retrieve Data → Answer

---

# ✅ Milestone 4 – UI Development & Integration

Tasks Completed:
- Built UI using Streamlit  
- Integrated backend with frontend  
- Enabled real-time question answering  
- Improved UI design (chat-style)  
- Removed dataset preview for clean interface  

Output:
Interactive question-answering system.

---

# ⚙️ Installation & Setup

1. Clone Repository:
git clone https://github.com/yourusername/AI_Knowledge_Graph_Builder.git  
cd AI_Knowledge_Graph_Builder  

2. Create Virtual Environment:
python -m venv venv  

Activate:

Windows:
venv\Scripts\activate  

Mac/Linux:
source venv/bin/activate  

3. Install Dependencies:
pip install streamlit  
pip install sentence-transformers  
pip install faiss-cpu  
pip install numpy  

---

# ▶ Running the Project

streamlit run app.py  

---

# 📁 Project Structure

graphbuilder/
│
├── app.py
├── ingestion/
│   ├── __init__.py
│   └── data_loader.py
├── rag/
│   ├── qa_system.py
│   └── vector_store.py
├── data/
│   └── dataset.pkl
└── README.md

---

# 📊 Current Status

Milestone 1 – Data Processing ✅ Completed  
Milestone 2 – Knowledge Graph ✅ Completed  
Milestone 3 – RAG System ✅ Completed  
Milestone 4 – UI Development ✅ Completed  

---

# 📌 Future Enhancements

- Improve answer quality using LLMs  
- Add graph-based querying  
- Support multiple datasets  
- Deploy on cloud  
- Enhance UI with chat history  

---

# ✅ Final Outcome

The AI Knowledge Graph Builder successfully:

- Processes large datasets  
- Converts text into embeddings  
- Performs semantic search  
- Retrieves relevant information  
- Provides real-time answers  

This project demonstrates a complete AI pipeline for intelligent information retrieval.

---

⭐ If you found this project useful, consider giving it a star on GitHub!
