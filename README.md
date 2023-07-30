# Semantic Search Using Vector Databases

Code and slides for the talk I gave on this topic.
Here is the [presentation](https://1drv.ms/p/s!AlrxwtK7Qzt-qX_MKMqDwhdAyamF?e=L8s39U)

It has two notebooks:

[Notebook with Detailed Theory](./notebooks/DatahackSummit%20Semantic%20Search%20Theory.ipynb)

[Notebook with hands on Code](./notebooks/DatahackSummit%20Semantic%20Search%20using%20vector%20Databases.ipynb)



## About

Semantic Search is a project that implements an advanced search functionality using natural language processing and semantic similarity techniques. It enables users to input queries in a human-like manner and retrieve relevant search results based on the semantic meaning of the query.

This project aims to improve the search experience by going beyond traditional keyword-based searches and providing more accurate and contextually relevant results.

## Installation

To run the Semantic Search project locally, follow these steps:

1. Clone the repository:

```
gh repo clone deepanshululla/SemanticSearch
cd SemanticSearch
```

2. Install the required dependencies:

```
conda env create -f environment.yml
```

3. Run Docker-compose up for elasticsearch

```bash
docker-compose up -d
```



## Usage

1. Start the Jupyter notebook  server:

```
jupyter noptebook .
```

## Technologies Used

- Python
- Gradio (for the web interface)
- Hugging Face Transformers (for NLP models)
- Langchain
- chromio
- ElasticSearch
