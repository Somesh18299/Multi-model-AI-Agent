# Multipurpose-Agent

This project is a powerful, customizable AI chatbot system built with LangGraph, FastAPI, and Streamlit. It allows users to dynamically interact with LLMs (from OpenAI and Groq) with optional web search functionality via Tavily.

✨ **Features**
🧠 Choose between OpenAI or Groq models

🔍 Optional web search using Tavily

⚙️ Custom system prompts for flexible personality and behavior

🗨️ Streamlit UI for easy interaction

🚀 FastAPI backend with Swagger UI for testing

🧩 Tech Stack
    LangGraph – For ReAct-style agent creation

    LangChain – For LLM interfaces

    Groq & OpenAI – As LLM providers

    Tavily – For real-time web search results

    FastAPI – For backend API

    Streamlit – For frontend UI

    Pydantic – For schema validation

    dotenv – For managing API keys securely

🔧 Setup Instructions

1. Clone the Repository
`git clone https://github.com/Somesh18299/Multipurpose-Agent.git`
`cd Multipurpose-Agent`

2. Create & Activate Virtual Environment
Open bash, `python -m venv venv` and 
`venv\Scripts\activate`

3. Install Dependencies
`pip install -r requirements.txt`

4. Add Your .env File
Create a .env file in the root directory:

<pre>GROQ_API_KEY=your_groq_api_key 
OPENAI_API_KEY=your_openai_api_key 
TAVILY_API_KEY=your_tavily_api_key </pre>

🚀 Running the App

1. Start the FastAPI Backend
`python backend.py`
Access API docs at: http://127.0.0.1:9999/docs

2. Start the Streamlit UI
`streamlit run frontend.py`
Interact with the chatbot at: http://localhost:8501

| Provider | Models                              |
|----------|-------------------------------------|
| Groq     | llama-3.3-70b-versatile, mixtral-8x7b-32768 |
| OpenAI   | gpt-4o-mini                         |


🤝 Contributions
Pull requests and suggestions are welcome!