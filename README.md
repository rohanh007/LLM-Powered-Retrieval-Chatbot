# LLM-Powered Retrieval Chatbot

An Intelligent AI-powered Chatbot using LangChain, RAG, and Multi-Tool Agents

This project implements an Agentic Chatbot that leverages LangChain, Retrieval-Augmented Generation (RAG), and Vector Databases to provide accurate, context-aware, and real-time answers.
The chatbot can fetch information from PDFs, documents, weather APIs, and the web, intelligently deciding when to use tools versus internal reasoning.

✨ Features

🧠 Agentic Reasoning → Uses LangChain’s agent framework to decide when and how to use tools

📄 PDF & Document Search → Retrieves relevant answers from ingested documents using a VectorDB

🌐 Web & Weather Integration → Fetches real-time data from external sources when required

🗣 Context-Aware Conversations → Maintains chat history for smoother, continuous interactions

⚡ Fast & Optimized → Loads the vector database only once to boost performance

🎨 Interactive UI → Built with Streamlit for a seamless user experience

🛠️ Tech Stack

Python 🐍

LangChain → For agent orchestration and tool integration

Vector Database → For document embeddings & retrieval

OpenAI / LLMs → For generating conversational responses

Streamlit → For a clean and interactive frontend

Google Serper API → For web search

⚡ Installation & Setup
1. Clone the Repository
- git clone https://github.com/rohanh007/LLM-Powered-Retrieval-Chatbot.git
- cd Agentic-Rag-Chatbot

2. Create a Virtual/Conda Environment
- conda create -n agentic_rag python=3.10
- conda activate agentic_rag

3. Install Dependencies
- pip install -r requirements.txt

4. Run the Application
- streamlit run app.py



Future Enhancements

🔹 Add support for multi-PDF simultaneous retrieval

🔹 Integrate YouTube transcript search

🔹 Enhance conversational memory for better context tracking

🔹 Add authentication for secure document uploads

🔹 Seamless MCP Protocol Integration → Enable a more sustainable and stable connection with external data sources using the Model Context Protocol (MCP)
