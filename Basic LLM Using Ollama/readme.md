

This repository contains step-by-step examples and small projects exploring **LangChain**, **OpenAI**, and **Ollama** integrations.  
Each subfolder demonstrates a specific concept — from basic API calls to embeddings and vector storage.

---

## 📂 Project Structure

1-Basics+Of+Langchain/
│
├── 1.1-openai/ # Intro to LangChain with OpenAI models
├── 1.2-ollama/ # Using Ollama locally with LangChain
│ ├── 1.2.1-Simpleapp.ipynb
│ └── app.py # Streamlit app entry point
│
├── 3.2-DataIngestion/ # Data loading and processing examples
├── 3.3-Data Transformer/ # Data cleaning, parsing, and transformation logic
├── 4-Embeddings/ # Text embeddings using OpenAI / HuggingFace
├── 5-VectorStore/ # Storing embeddings in FAISS / Chroma
│
├── venv/ # (Optional) local virtual environment
├── .env # Environment variables (API keys)
└── requirements.txt # Python dependencies


## 🚀 Running the Streamlit App

Make sure you have your environment active (Conda or venv):

```bash
conda activate langchain_env
# or
.\venv\Scripts\activate

Then install dependencies:

pip install -r requirements.txt

Run the Streamlit app:

streamlit run 1.2-ollama/app.py
