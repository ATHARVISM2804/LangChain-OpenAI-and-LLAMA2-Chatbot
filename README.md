# LangChain Streamlit Demo

This project demonstrates how to build a simple chatbot using **LangChain**, **Streamlit**, and either the **OpenAI API** or **LLaMA2 via Ollama**. It includes two versions:

- `LangChain + OpenAI` using GPT-3.5-Turbo
- `LangChain + LLaMA2` using the Ollama runtime

## 🔧 Features

- Interactive chatbot UI with Streamlit
- Modular chain using `ChatPromptTemplate`, LLM, and `StrOutputParser`
- Support for `.env` file for API key management
- LangSmith integration for LangChain tracing and debugging

---

## 📁 Project Structure

├── app_openai.py # Chatbot using OpenAI API
├── app_llama2.py # Chatbot using LLaMA2 via Ollama
├── .env # Environment variables (ignored by Git)
├── .gitignore # Git ignore configuration
├── requirements.txt # Python dependencies
└── README.md # Project documentation

yaml
Copy
Edit

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/langchain-streamlit-demo.git
cd langchain-streamlit-demo
2. Create and activate a virtual environment
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install the dependencies
bash
Copy
Edit
pip install -r requirements.txt
4. Set up your .env file
Create a .env file in the project root and add the following:

env
Copy
Edit
OPENAI_API_KEY=your_openai_api_key
LANGCHAIN_API_KEY=your_langsmith_api_key  # optional for Langsmith tracing
▶️ Running the Apps
🔹 OpenAI-based Chatbot
bash
Copy
Edit
streamlit run app_openai.py
🔹 LLaMA2-based Chatbot (Ollama required)
Make sure Ollama is installed and LLaMA2 is available:

bash
Copy
Edit
ollama run llama2
Then run the app:

bash
Copy
Edit
streamlit run app_llama2.py
⚙️ .gitignore Example
Make sure your .gitignore file includes:

bash
Copy
Edit
# Ignore virtual environments and env files
venv/
.env
__pycache__/
🧠 Built With
LangChain

OpenAI

Ollama

Streamlit

LangSmith

📄 License
This project is licensed under the MIT License.

🙌 Acknowledgements
Built for demo purposes by [Your Name] using cutting-edge LLM frameworks.

yaml
Copy
Edit

---

Let me know if you'd like this in `Markdown` preview mode, or want me to generate a `requirements.txt` file too.








