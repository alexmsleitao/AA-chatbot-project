# AA-chatbot-project
The goal of this project was to create a chatbot trained according to the AA principles, that can be used by AA football players

#Here’s how I want to built it:
- Connected to a Dropbox App folder, where all the documents are stored
- Pre-processed and chunked content for better retrieval accuracy
- Utilised the HuggingFace sentence-transformers model (all-MiniLM-L6-v2) with storage in a PostgreSQL + pgvector database
- Built the RAG pipeline using LangChain and the free DeepSeek LLM model
- Designed a simple, coach-friendly Streamlit UI
- Secured access with token-based authentication

#⚙️ Tech Stack:
Python 🐍 
Dropbox API (document integration) 📃 
LangChain (RAG pipeline) 🪈 
DeepSeek R1 LLM on Openrouter (free model) 🤖 
PostgreSQL + pgvector (cloud vector DB) 💾 
Streamlit (UI) 💻 

