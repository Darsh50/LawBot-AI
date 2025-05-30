# LawBot-AI
An AI-powered chatbot that helps users understand and query legal documents using Retrieval-Augmented Generation (RAG) and GPT-based models.

# Technical Architecture
The chatbot integrates several advanced technologies:

- Large Language Model (LLM): Utilizes ChatGPT 4.0 for generating human-like responses.

- Vector Database: Implements ChromaDB to store and retrieve document embeddings efficiently.

- Embedding Functions: Leverages OpenAI's embedding models to convert textual data into vector representations.

- Agent Framework: Employs LangChain to manage the interaction between components and streamline the retrieval and generation process.

This architecture enables the system to process extensive legal documents and deliver precise answers, demonstrating the LLM's proficiency in interpreting legal terminology.

For the purpose of this demo, the context is The Artificial Intelligence Act, document adopted by EU Parliament on 13 March 2024. The system could be easily extended to many other legal papers.

### Installing
After cloning the repository the OpenAI key needs to be added as an environmental variable with the name OPENAI_API_KEY.
```bash
export OPENAI_API_KEY=your_key_value_here
```
After that it should be all fine. To run it localy, in the app folder use:
```bash
streamlit run app.py
```
