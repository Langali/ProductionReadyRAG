# ProductionReadyRAG
Creating a Production Ready Retrieval Augmented Generation (RAG) Agentic Workflow with OpenAI API for PDF ingestion

Demo:

[Production RAG Demo](https://youtu.be/OrgrrwHXUrY)

This project was tutorial based: [Tutorial](https://www.youtube.com/watch?v=AUQJ9eeP-Ls)

The goal of this project was to develop an understanding behind agentic workflows and the tools that make them production ready.

Main Tools used:

LLM Model
- OpenAI API used
- [OpenAI](https://openai.com/index/openai-api/)

Qdrant - [Vector Database Operations](https://shorturl.at/At57h)]

- specialized database that stores and searches through embeddings
searches by similarity instead of exact matches
- Stores embeddings of PDF chunks 
- When LLM is prompted, vector similarity is compared between prompt and chunks to find most relevant context

Inngest - [Workflow Orchestrator](https://www.inngest.com/)

- Manages complex, multi-step workflows 
- Makes the process behind agentic workflows reliable with retries in cases of failure and observability of errors - you can see each step being run in the dashboard
  
Docker and Streamlit

- Docker was additionally used in this tutorial for the Qdrant Container
- Streamlit used for the frontend application
[Docker](https://www.docker.com/)
[StreamLit](https://streamlit.io/)

