🤖 LangGraph Chatbot

An AI-powered chatbot built with LangGraph, Groq LLaMA3-70B, and Streamlit, designed to demonstrate modern conversational AI with real-time streaming responses and a modular backend/frontend architecture.

✨ Features

⚡ Groq LLaMA3-70B Integration → Ultra-fast LLM responses.

🧠 LangGraph State Management → Handles conversations with memory checkpoints.

💬 Interactive Streamlit Chat UI → Sleek interface with real-time streaming output.

📂 Modular Architecture → Clear separation of backend (langgraph_backend.py) and frontend (streamlit_frontend_streaming.py).

🔒 Secure Setup → Environment variables stored safely in .env (ignored by Git).

🛠️ Tech Stack

LangGraph → Conversation flow & state graph

LangChain → Message handling

Groq LLaMA3-70B → Large language model for inference

Streamlit → Chat interface frontend

Python → Core implementation

🖼️ Project Architecture
langgraph_chatbot/
├── langgraph_backend.py          # Backend chatbot logic (LangGraph + Groq)
├── streamlit_frontend_streaming.py # Frontend Streamlit chat UI
├── .env.example                  # Example environment variables
├── .gitignore                    # Git ignore file (protects .env)
└── README.md                     # Project documentation

🚀 Getting Started
1️⃣ Clone the repository
git clone https://github.com/YOUR-USERNAME/LangGraph-Chatbot.git
cd LangGraph-Chatbot

2️⃣ Setup environment

Create and activate a virtual environment:

python -m venv venv
venv\Scripts\activate   # Windows
# OR
source venv/bin/activate # Mac/Linux


Install dependencies:

pip install -r requirements.txt

3️⃣ Configure API Keys

Create a .env file in the root directory:

GROQ_API_KEY=your_api_key_here
OPENAI_API_KEY=your_openai_key_here   # optional


(An .env.example is included for reference.)

4️⃣ Run the chatbot
streamlit run streamlit_frontend_streaming.py


Open http://localhost:8501
 in your browser 🎉

🎯 Why This Project Stands Out

✅ Showcases modern AI frameworks (LangGraph + Groq + LangChain).
✅ Implements streaming responses in a professional UI (Streamlit).
✅ Uses a modular backend/frontend design → easy to scale & maintain.
✅ Secure handling of API keys via .env.

This project demonstrates the ability to design, build, and deploy conversational AI systems with production-ready practices — a key skill for AI/ML Engineer, Data Engineer, or Applied Scientist roles.

📸 Demo (Optional)

👉 Add a GIF or screenshot of the chatbot UI here to grab attention.

📩 Contact

If you’re interested in this project or want to collaborate:

Author: Krish Shah

GitHub: KRISHSHAH1203

LinkedIn: https://www.linkedin.com/in/krishshah1203/

⚡ “Built with LangGraph, powered by Groq, and deployed with Streamlit.”
