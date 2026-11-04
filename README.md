# An-Intelligent-RAG-Powered-HR-Support-Assistant
A smart conversational assistant that helps employees find accurate answers to Company policies, company guidelines, other queries using Retrieval-Augmented Generation

📌 Project Overview
PeopleDesk AI is an AI-powered HR support assistant that uses Retrieval-Augmented Generation (RAG) to answer employee questions based on HR policies and employee handbook documents.

Instead of manually searching through lengthy HR documents, employees can ask questions in natural language and receive relevant answers.

🎯 Key Features
- Upload and process HR handbook PDFs.
- Extract and split documents into chunks.
- Generate vector embeddings.
- Store embeddings using FAISS.
- Retrieve relevant information using semantic search.
- Generate contextual answers using Google Gemini.
- Interactive chatbot interface using Gradio.


🏗️ Architecture

company policy PDF --> Document Processing-->Text Chunking-->Embeddings-->FAISS Vector Database-->Retriever + Gemini LLM-->HR Assistant Answer

🛠️ Technologies Used

- Python	                          
- LangChain       	                
- Gemini           	                
- FAISS           	                
- Gradio	                         
- Sentence Transformers	            


  
