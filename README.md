# Medical-Chatbot
Built an intelligent medical chatbot using open-source tools. The project utilizes HuggingFace for embeddings, Faiss (CPU) for vector storage, Mistral for NLP, and Streamlit for an interactive interface. The goal is to create an AI-powered healthcare solution for providing medical information and guidance when multiple pdfs are uploaded.

# Installation:

Python versions 3.11 or 3.10

pip install pipenv

pipenv install langchain langchain_community langchain_huggingface faiss-cpu pypdf

pipenv install huggingface_hub

pipenv install streamlit

# Execution:
pipenv run python create_memory_for_llm.py

python connect_memory_with_llm.py

pipenv exit -- exiting from virtual environment

streamlit run medibot.py

