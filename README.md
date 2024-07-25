# Exploring LangGraph and Advanced Retrieval-Augmented Generation (RAG) Techniques

This repository contains notebooks and resources for exploring LangGraph and advanced Retrieval-Augmented Generation (RAG) techniques, including Adaptive RAG, Corrective RAG, and Self RAG. 

## Prerequisites

To run the notebooks, you will need:

- **Ollama**: Install Ollama from [here](https://ollama.com).
- **Llama3 Model**: Use the following command to pull the Llama3 8B model:

`ollama pull llama3:8b`


## Notebooks

### 1. `langgraph-advanced-rag.ipynb`

This notebook demonstrates the use of LangGraph to orchestrate steps in a Generative AI application and covers the following advanced RAG techniques:
- Adaptive RAG
- Corrective RAG
- Self RAG

### 2. `db_creation.ipynb`

This notebook can be used to create an SQLite database required for some of the examples in the `langgraph-advanced-rag` notebook.

## Getting Started

1. Clone the repository:
`git clone https://github.com/AnudeepGadi/Bank-GenAI-Bot.git`<br>
`cd Bank-GenAI-Bot`

2. Install the necessary Python packages:
`pip install -r requirements.txt`

3. Pull the Llama3 8B model using Ollama:
`ollama pull llama3:8b`


4. Run the `db_creation.ipynb` notebook to create the SQLite database.

5. Open and run the `langgraph-advanced-rag.ipynb` notebook to explore LangGraph and advanced RAG techniques.

## References

- Sophia Young and Lance Martin - "Advance RAG Control Flow with Mistral and LangChain: Corrective RAG, Self-RAG, Adaptive RAG"
- [LangGraph Documentation](https://langgraph-docs.com)
- [Ollama Documentation](https://ollama.com/docs)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
