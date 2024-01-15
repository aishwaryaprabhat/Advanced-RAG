# Performing, Evaluating & Tracking Advanced RAG (ft. AzureML, LlamaIndex & Ragas) 🚀
<a href="https://colab.research.google.com/github/aishwaryaprabhat/Advanced-RAG/blob/main/Advanced_RAG.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
<a href="https://www.linkedin.com/pulse/performing-evaluating-tracking-advanced-rag-ft-azureml-prabhat-i1rkc/" target="_parent"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Article"/></a>

![](assets/rag.png)

## Table of Contents 📋
1. [Introduction 🌟](#introduction-)
2. [RAG Techniques 🛠️](#rag-techniques-️)
3. [Installation 📥](#installation-)
4. [Usage 💻](#usage-)
5. [Evaluating RAG Techniques 📊](#evaluating-rag-techniques-)
6. [Experiment Tracking 📈](#experiment-tracking-)
7. [License 📄](#license-)
8. [References & Further Reading 📚](#references--further-reading-)

## Introduction 🌟
The `Advanced_RAG.ipynb` notebook in this repository provides an in-depth analysis and implementation of three RAG techniques and six RAG evaluation techniques. Additionally, it demonstrates how to track evaluation experiments using MLflow. 

Checkout the accompanying <a href="https://www.linkedin.com/pulse/performing-evaluating-tracking-advanced-rag-ft-azureml-prabhat-i1rkc/" target="_parent"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Article"/></a> Article!

## RAG Techniques 🛠️
The notebook details the following RAG techniques:
- **Chunks with Overlap 🧩**: Splits the document into overlapping chunks of text.
- **Sentence Window Retrieval 🪟**: Utilizes surrounding sentences as context for retrieval.
- **Hierarchical Automerge Retrieval 🔼**: Combines hierarchical data organization with retrieval augmentation for more contextually rich results.

## Evaluating RAG Techniques 📊
The notebook demonstrates the evaluation of RAG techniques using the following metrics:
- **Context Precision 🔍**
- **Context Recall 🎯**
- **Faithfulness 🤝**
- **Answer Relevancy 🎯**
- **Answer Similarity ↔️**
- **Answer Correctness ✅**

## Experiment Tracking 📈
The experiment tracking section showcases how to use Microsoft Azure ML Studio and MLflow for tracking and analyzing the results of your RAG evaluations. 

## Installation 📥
While the steps detailed below are also in the `Advanced_RAG.ipynb` notebook for running in a hosted environment like Google Colab or AzureML Studio, you may choose to set up your environment locally.

1. **Clone the Repository** 📂: 
   ```bash
   git clone https://github.com/your-username/Advanced-RAG.git
   cd Advanced-RAG
   ```

2. **Install Dependencies** 💾: 
   Make sure you have Python 3.6+ installed, then run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Data Preparation** 📊:
   Run the `download_dataset.sh` script to download the necessary data:
   ```bash
   chmod +x download_dataset.sh
   ./download_dataset.sh
   ```

## Usage 💻
- Open the `Advanced_RAG.ipynb` notebook in a Jupyter environment.
- Follow the instructions and code cells in the notebook to explore the various RAG techniques and evaluations.


## License 📄
This project is licensed under the terms of the [LICENSE](LICENSE) file in this repository.

---

I hope this notebook empowers you to delve into the world of RAG and enhances your understanding and capabilities in this exciting area of NLP and AI research. Happy experimenting!

---
