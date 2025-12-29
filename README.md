# Customer Support Chatbot

This project is a customer support chatbot built with **FastAPI** and **Ollama LLM**.  
It allows users to send queries and get AI-generated responses in real-time.

## How to Run

1. Clone the repository:
```bash
git clone <your-repo-url>
cd ollama_project
2.Create the virtual envirment
python -m venv .venv
# Windows
.venv\Scripts\activate
3.Install dependencies:
pip install -r requirements.txt
4.Start the Ollama server:
ollama serve
5.Start the FastAPI app:
uvicorn chatbot:app --reload
6.Test the chatbot:
Open browser at http://127.0.0.1:8000/docs
Use the /chat POST endpoint to send messages and receive replies

Notes:

Ollama must be installed and running locally.
The chatbot uses the llama3.2 model by default.
Only one Ollama server can run on port 11434 at a time.


