Cambridge University AI Advisor Chatbot
An LLM-powered RAG system for academic advising, admissions guidance, and university information retrieval.

1.	Project Overview
The Cambridge University AI Advisor Chatbot is an intelligent, domain-specialized assistant designed to answer questions about:
•	Admissions
•	Courses & departments
•	Fees & funding
•	Deadlines & requirements
•	Scholarships
•	College system structure
•	General student life

This project showcases real-world Retrieval-Augmented Generation (RAG) architecture, implemented using LangChain, FAISS vector search, and modern LLMs.

   2.  Key Features
•	RAG-Based Answer Generation
•	Semantic Search with FAISS Vector Store
•	Automated Document Pipeline
•	Conversational Memory
•	Google Colab–friendly
•	Modular Codebase


   3. Example Queries
•	“What are the entry requirements for Cambridge Computer Science?”
•	“How does the Cambridge collegiate system work?”
•	“Which scholarships exist for international applicants?”

   4. How to Run the Project
Option 1 — Google Colab
1. Upload university documents into data/raw/
2. Run all cells

Option 2 — Run Locally
git clone https://github.com/p-alaita/Cambridge-University-Chatbot.git
pip install -r requirements.txt
python src/ingest.py
python src/chatbot.py

Requirements
•	langchain
•	langchain-core
•	langchain-community
•	langchain-openai
•	sentence-transformers
•	faiss-cpu
•	tiktoken
•	numpy
•	pandas
•	python-dotenv

Performance Notes
•	Strong retrieval accuracy
•	Low hallucination rate
•	Flexible architecture

Ethical & Data Usage Notes
All documents used are publicly available.

Why This Project Stands Out
•	Real-world AI architecture
•	NLP engineering skills
•	End-to-end ML
•	Modern LangChain usage

Author
Patience Alaita
