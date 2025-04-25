# ArtiQuery 🧐

**ArtiQuery** is a Streamlit-based application that allows users to input article URLs, extract and process their content using AI, and ask questions based on the synthesized information. It's powered by Google's Gemini model and FAISS for semantic search, delivering concise and context-aware answers from multiple sources.

## 🚀 Features

- 🔗 Input up to 3 article URLs.
- 🧠 Process and embed article content using HuggingFace sentence transformers.
- 🗂️ Store and retrieve document embeddings with FAISS.
- 🤖 Ask questions and get answers synthesized by Google's Gemini (`gemini-1.5-pro-latest`).
- 📚 See which articles were used as sources for the response.
- 🌐 Accessible via a public link using Ngrok.

# 🧠 Tech Stack
Frontend: Streamlit

LLM: Google Gemini via LangChain

Embeddings: Sentence-Transformers (all-mpnet-base-v2)

Vector DB: FAISS

URL Loading: Unstructured

Public URL: Ngrok

## 🛠️ Setup

1- Create a Virtual Environment using the commands : 
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

2- Required installation : 
To install the required packages for this project check the installations in the ArtiQuery.ipynb file , or jsut use the command : pip install -r requirements.txt

3- Set Up Environment Variables :
GEMINI_API_KEY=your_google_gemini_api_key
NGROK_AUTH_TOKEN=your_ngrok_auth_token

4- Create a main.py file and paste the code of the main cell that writes the app.py and run the app using the command (python main.py)
   
