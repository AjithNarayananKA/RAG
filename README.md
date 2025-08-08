# Retrieval-Augmented Generation (RAG) Implementations

This repository provides various implementations of Retrieval-Augmented Generation (RAG) pipelines, showcasing different frameworks and tools. Each implementation is contained in its own directory, offering a modular way to explore and compare different approaches to building RAG applications.

## 🌟 Overview

This repository is a collection of RAG projects demonstrating how to leverage the power of large language models (LLMs) with external knowledge sources. You will find examples using popular frameworks like Haystack, LlamaIndex, and Langchain, and integrations with models such as Mistral and OpenAI.

## 📂 Project Structure

The repository is organized as follows:

```
.
├── RAG App using Haystack/
├── RAG App using LLamaindex and Mistral/
├── RAG App using Langchain MistralAI Weviate/
├── RAG App using Langchain OpenAI FAISS/
├── .gitignore
├── RAG_pipeline_from_Scratch.ipynb
└── requirements.txt
```

## 🚀 Implementations

Here's a brief overview of each implementation:

### 1\. RAG App using Haystack

  * **Directory**: `RAG App using Haystack/`
  * **Description**: This application demonstrates how to build a RAG pipeline using the [Haystack framework](https://haystack.deepset.ai/). It provides a complete example of setting up a Haystack-based retrieval and generation system.

### 2\. RAG App using LlamaIndex and Mistral

  * **Directory**: `RAG App using LLamaindex and Mistral/`
  * **Description**: This implementation showcases the use of [LlamaIndex](https://www.llamaindex.ai/) for data indexing and retrieval, coupled with the [Mistral](https://mistral.ai/) language model for generation. It's a great example of how to combine these powerful tools to create a robust RAG system.

### 3\. RAG App using Langchain, MistralAI, and Weaviate

  * **Directory**: `RAG App using Langchain MistralAI Weviate/`
  * **Description**: This project leverages the [Langchain](https://www.langchain.com/) framework to build a RAG pipeline. It uses [MistralAI](https://mistral.ai/) for generation and the [Weaviate](https://weaviate.io/) vector database for efficient document storage and retrieval.

### 4\. RAG App using Langchain, OpenAI, and FAISS

  * **Directory**: `RAG App using Langchain OpenAI FAISS/`
  * **Description**: This application also uses [Langchain](https://www.langchain.com/) but demonstrates how to integrate it with [OpenAI's models](https://openai.com/) and [FAISS (Facebook AI Similarity Search)](https://github.com/facebookresearch/faiss) for fast in-memory similarity searches.

### 5\. RAG Pipeline from Scratch

  * **File**: `RAG_pipeline_from_Scratch.ipynb`
  * **Description**: This Jupyter Notebook provides a step-by-step guide to building a RAG pipeline from the ground up. It's an excellent resource for understanding the fundamental components of a RAG system without relying on high-level frameworks.

## ⚙️ Getting Started

To get started with any of the implementations in this repository, follow these steps:

### Prerequisites

  * Python 3.8 or higher
  * pip for package management

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/AjithNarayananKA/RAG.git
    cd RAG
    ```

2.  **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

    *Note: Each sub-directory might have its own specific dependencies. Make sure to check the respective folders for any additional `requirements.txt` files.*

### Running the Applications

Navigate to the directory of the implementation you want to run and follow the instructions in the respective project's files. For example, to run the Haystack application:

```bash
cd "RAG App using Haystack"
# Follow instructions in the project's README or Python scripts
```

## 🤝 Contributing

Contributions are welcome\! If you have suggestions for improvements or want to add new RAG implementations, please feel free to:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/your-feature-name`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'Add some feature'`).
5.  Push to the branch (`git push origin feature/your-feature-name`).
6.  Open a pull request.

## 📜 License

This project is unlicensed. Please add a license file if you wish to specify usage terms.
