# Physics & Astronomy Chatbot (RAG-based)
This project is an AI-powered chatbot designed to answer questions related to Physics and Astronomy. It uses a Retrieval-Augmented Generation (RAG) architecture with the Meta-LLaMA model via the Together API. The chatbot enables users to ask complex scientific questions and receive accurate, context-aware responses in real time.

The full-stack application includes a React.js frontend and a Flask-based backend, with successful cloud deployment using AWS services.

## Purpose
The primary goal of this chatbot is to serve as an intelligent assistant for students, educators, and science enthusiasts by providing high-quality, explainable answers on Physics and Astronomy topics. It demonstrates how modern LLMs and RAG systems can be used for domain-specific knowledge delivery.

## Usage
1. Input a Physics or Astronomy question into the chatbot.
2. The backend retrieves relevant context using a RAG pipeline.
3. The Meta-LLaMA model (via Together API) generates a response.
4. The frontend displays a chat-style interaction interface.
5. Supports cloud deployment.

## Tech Stack
1. Frontend: React.js (TypeScript, Vite)
2. Backend: Flask (Python), Together API, FAISS for vector search
3. AI Model: Meta-LLaMA via Together API (RAG pipeline)
4. Cloud Deployment:
    - Frontend: AWS Amplify
    - Backend: AWS Elastic Beanstalk
Other Tools: Flask-CORS, dotenv, PyPDF2, FAISS, Tokenizers

Live Demo
**Frontend (React)**: [Visit Chatbot UI](https://astrobot-frontend-h0zs.onrender.com)
