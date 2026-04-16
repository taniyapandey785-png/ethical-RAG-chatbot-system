Ethcal-RAG-Chatbot System

This project implements a **Retrieval-Augmented Generation (RAG) chatbot** using Flowise. It combines document retrieval with Large Language Models (LLMs) to generate accurate, context-aware, and reliable responses.

---

## Features

-  Upload and process custom documents
-  Intelligent document retrieval using vector embeddings
-  Context-aware response generation with LLM (Mistral AI)
-  Reduces hallucinations and misinformation
-  Improves transparency and explainability
-  Scalable and modular architecture

---

##  System Architecture

The project includes the following components:

1. **File Loader** – Uploads and reads documents  
2. **Text Splitter** – Breaks text into smaller chunks  
3. **Embeddings Model** – Converts text into vector format  
4. **Vector Store** – Stores embeddings for retrieval  
5. **Retriever** – Fetches relevant data  
6. **LLM (Mistral AI)** – Generates final responses  
7. **Conversational Chain** – Maintains chat context  
<img width="1827" height="775" alt="image" src="https://github.com/user-attachments/assets/f77a22a1-3b25-476b-80c7-bf755a2c83af" />

<img width="1890" height="869" alt="Screenshot 2026-04-08 155251" src="https://github.com/user-attachments/assets/d611a881-39d5-4aa8-b7c2-02e107f62dd0" />

---

## Tech Stack

- Flowise
- Mistral AI (LLM)
- Google Generative AI Embeddings
- Vector Database (In-Memory)

---

## How It Works

1. Upload a document  
2. System splits and converts it into embeddings  
3. Stores embeddings in vector database  
4. User asks a question  
5. Relevant data is retrieved  
6. LLM generates a grounded response  

---

## Use Cases

- HR Policy Assistant  
- Educational Chatbots  
- Legal/Healthcare Support Systems  
- Knowledge Base Assistants  

---

## Limitations

- Depends on quality of uploaded data  
- May inherit bias from documents  
- Not a complete AI ethics solution  

---

## Conclusion

This project demonstrates how RAG can enhance AI reliability by improving factual accuracy, reducing hallucinations, and increasing transparency, making AI systems more trustworthy and effective.

---

##  Author

Taniya pandey
