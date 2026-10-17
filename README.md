# RAG Chatbot – Toronto Travel Assistant 🤖

An AI-powered chatbot that answers travel-related questions about Toronto, Canada, using Retrieval-Augmented Generation (RAG).

## 🚀 Features
- Answers questions about Toronto tourist attractions.
- Provides information about restaurants, transportation, and travel itineraries.
- Retrieves relevant information from a travel guide.
- Generates answers using a language model.
- Provides an interactive chat interface.

## 🛠️ Technologies Used
- Python
- Streamlit
- LangChain
- Hugging Face Embeddings
- Pinecone Vector Database
- OpenAI API

## ⚙️ How It Works
1. Loads the Toronto travel guide.
2. Splits the document into smaller text chunks.
3. Converts text into embeddings.
4. Retrieves relevant information using Pinecone.
5. Generates answers using a language model.
6. Displays responses through the Streamlit interface.

## 📦 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/aabdulhanan-spec/RAG_CHATBOT_AI-BOOTCAMP.git
cd RAG_CHATBOT_AI-BOOTCAMP
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Configure API Keys
Set up the required OpenAI and Pinecone credentials using environment variables. Never upload your API keys to GitHub.

### 4. Run the Application
```bash
streamlit run streamlitMain.py
```

## 🎯 Project Objective
The goal of this project is to demonstrate how Retrieval-Augmented Generation, vector databases, embeddings, and large language models can be combined to build an AI-powered chatbot.

## 🔮 Future Improvements
- Support for PDF document uploads.
- Display sources used to generate answers.
- Improve error handling and response accuracy.
- Add more travel information.

## 👨‍💻 Author
Abdul Hanan

## 🏷️ Topics
Python · RAG · Artificial Intelligence · Machine Learning · LangChain · Streamlit · Pinecone · Generative AI
