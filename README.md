# 🩺 MediLens AI

MediBot AI is a Medical RAG (Retrieval-Augmented Generation) chatbot built using Streamlit, LangChain, FAISS, Groq LLM, and Google Gemini Vision.

It allows users to:

- 💬 Ask medical questions in natural language
- 📚 Retrieve answers from The Gale Encyclopedia of Medicine
- 🔍 Perform semantic search using FAISS Vector Database
- 🖼 Upload medical images for AI-powered analysis
- 🤖 Get contextual answers powered by LLMs

---

## 🚀 Features

### Medical RAG Chatbot
- Uses Retrieval-Augmented Generation (RAG)
- Retrieves relevant medical information from a vector database
- Answers based on trusted encyclopedia content

### AI Medical Assistant
- Supports natural language conversations
- Maintains chat history during sessions
- Friendly and interactive interface

### Medical Image Analysis
- Upload skin conditions, rashes, acne, etc.
- AI analyzes uploaded image
- Returns possible observations and explanations

### Source Referencing
- Displays retrieved source documents
- Shows page references from the medical encyclopedia

---

## 🛠 Tech Stack

### Frontend
- Streamlit

### LLM
- Groq (Llama 3.3 70B)

### Vision Model
- Google Gemini

### Embeddings
- HuggingFace Embeddings
- all-MiniLM-L6-v2

### Vector Database
- FAISS

### Frameworks
- LangChain
- LangChain Community
- LangChain HuggingFace

---

## 📂 Project Structure

```text
MediBot_Rag
│
├── data/
│   └── Medical PDF Source
│
├── vectorstore/
│   └── db_faiss/
│       ├── index.faiss
│       └── index.pkl
│
├── uploaded_images/
│
├── page_images/
│
├── medibot.py
├── requirements.txt
├── .env
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/Muskansh7/Medibot_Rag.git
cd Medibot_Rag
```

### Create Virtual Environment

```bash
python -m venv venv
```

Activate:

Windows:

```bash
venv\Scripts\activate
```

Linux / Mac:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file:

```env
GROQ_API_KEY=your_groq_api_key
GEMINI_API_KEY=your_gemini_api_key
```

---

## ▶️ Run Application

```bash
streamlit run medibot.py
```

Application will be available at:

```text
http://localhost:8501
```

---

## 🌐 Deployment

This project can be deployed on:

- Streamlit Community Cloud
- Render
- Hugging Face Spaces
- AWS EC2

## 📸 Screenshots
<img width="1919" height="913" alt="image" src="https://github.com/user-attachments/assets/06cd67dc-e80e-438b-b66b-ed1c4e96ae1f" />


### Medical Question Answering

- Ask medical questions
- Retrieve context-aware answers
- Display source references

### Image Analysis

- Upload medical images
- AI analyzes image content
- Generates observations

---

## 🔮 Future Improvements

- Voice Input
- Medical Report Summarization
- Symptom Checker
- Multi-turn Memory
- Disease Image Retrieval
- Doctor Recommendation System
- PDF Upload Support

---

## ⚠️ Disclaimer

MediBot AI is intended for educational and informational purposes only.

It is not a substitute for professional medical advice, diagnosis, or treatment. Always consult qualified healthcare professionals for medical concerns.

---

## 👩‍💻 Author

**Muskan Sharma**

GitHub:
https://github.com/Muskansh7

---

⭐ If you found this project useful, consider giving it a star.
