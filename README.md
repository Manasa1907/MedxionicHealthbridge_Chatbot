# MedxionicHealthbridge_Chatbot
This code implements the AI which responds to queries related to concepts of biomedical engineering and embedded with respect to the ongoing projects of the organization.

Overview
MedXionic HealthBridge is an AI-powered chatbot built using Python and LangChain's Retrieval-Augmented Generation (RAG) framework. The chatbot is designed to provide answers based on predefined biomedical documents and structured prompts.

Features
- Retrieval-augmented chatbot using LangChain
- Document-based question-answering
- FAISS-based vector search for efficient retrieval
- Custom prompt-based AI responses

Prerequisites
Ensure you have the following installed on your system:
- Python 3.8+
- OpenAI API Key


Current Status
- The chatbot's core logic is implemented using Python and LangChain.
- Streamlit is considered for the user interface but is not yet integrated.
- The application is still in the development phase and not ready for deployment.

How It Works
1. Document Processing: The chatbot processes predefined biomedical documents.
2. Retrieval & Response:
   - Uses FAISS for fast document search.
   - Leverages LangChain's retrieval-based AI to generate precise answers.
3. Chatbot Interaction: The chatbot can answer questions based on available document data.

Dependencies
- `openai`
- `langchain_community`
- `langchain_openai`
- `faiss-cpu`
- `pypdf`

Limitations
- The chatbot strictly answers based on the given document.
- The Streamlit interface is not yet implemented.
- The project is still in its initial phase and requires further testing and enhancements.

Contact
For further queries, please contact MedXionic Support at support@medxionic.com


