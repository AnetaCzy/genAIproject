# genAIproject

![Python Version](https://img.shields.io/badge/python-3.9+-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)

## Table of Contents
- [Description](#description)
- [Applications](#applications)
  - [App 1: Research Paper Indexer](#app-1-research-paper-indexer)
  - [App 2: Semantic Research Query](#app-2-semantic-research-query)
- [Installation & Setup](#installation--setup)
- [Project Structure](#project-structure)
- [License](#license)

---

## Description  
`genAIproject` is an interactive generative AI system for academic research. It allows users to search, index, and query scientific papers from **arXiv**, converting them into embeddings for AI-powered exploration and knowledge retrieval.  

---

## Applications  

### App 1: Research Paper Indexer  
The application allows users to enter a research topic. Once submitted, the system:  
1. Uses an agent to search **arXiv** for relevant papers.  
2. Retrieves and extracts the content of these papers.  
3. Converts the content into embeddings.  
4. Stores the embeddings in a **vector database** for efficient querying.  
5. Notifies the user once indexing is complete.  

### App 2: Semantic Research Query  
The application enables users to query the indexed knowledge base by entering research questions. The system:  
1. Uses semantic search to retrieve relevant papers from the vector database.  
2. Generates informative responses grounded in the retrieved papers.  
3. Provides proper citations, including links and metadata, to the original sources.  

---

## Installation & Setup  
(Optional) Create and activate a virtual environment:
    python -m venv venv
    source venv/bin/activate  # macOS/Linux
    venv\Scripts\activate     # Windows


Install dependencies:
    pip install -r requirements.txt

Set up API keys (if required, e.g., OpenAI):
    export OPENAI_API_KEY="your_api_key_here"  # macOS/Linux
    setx OPENAI_API_KEY "your_api_key_here"    # Windows


Launch Jupyter Notebook:
    jupyter notebook or jupyter lab


### Open app.ipynb and follow the workflow:

App 1: Enter a research topic to index papers.

App 2: Enter research questions to query the indexed knowledge base.

### Project Structure

<img width="558" height="127" alt="image" src="https://github.com/user-attachments/assets/986ab0bd-7680-40a8-882c-d95feb9a955b" />


License

This project is released under the MIT License.



1. Clone the repository:  
```bash
git clone https://github.com/AnetaCzy/genAIproject.git
cd genAIproject
