# LangGraph Chatbot

This project demonstrates a chatbot built using LangGraph. The chatbot integrates with a vector store for LangGraph-specific information and Wikipedia for general knowledge retrieval. 

## Features

* **LangGraph Integration:** Leveraging LangGraph's state management and execution flow for building a conversational AI application.
* **Vector Store:** Uses an AstraDB vector store to store and retrieve information related to LangGraph concepts.
* **Wikipedia Integration:** Integrates with Wikipedia to answer general knowledge questions.
* **Intelligent Routing:** Utilizes a structured output LLM to determine whether a question should be answered using the vector store or Wikipedia.
* **Chat History:** Maintains a chat history to provide context for the conversation.

## Requirements

* Python 3.7 or higher
* Google Colab or Jupyter environment
* Groq API key (stored in `GROQ_API_KEY` user data or .env file)
* AstraDB API endpoint and application token (stored in `ASTRA_DB_API_ENDPOINT` and `ASTRA_DB_APPLICATION_TOKEN` user data or .env file)

## Setup

Clone the repository:
```sh
> git clone https://github.com/Armaan457/CRUD-Agent.git
```
Install dependencies:

```sh
> pip install -r requirements.txt
```

You can now run the notebook `Langgraph_Chatbot.ipynb`
