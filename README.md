# RAG Dream Islands Project

This project implements a Retrieval-Augmented Generation (RAG) pipeline to support the Dream Islands initiative. It leverages advanced AI tools and libraries for embedding generation, text chunking, vector storage, and knowledge retrieval to provide AI-powered insights and solutions.

## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Usage](#usage)

## Overview

The RAG Dream Islands project combines AI technologies to enhance information retrieval and knowledge augmentation for a travel startup Dream Islands. It uses pre-trained models and state-of-the-art embedding techniques to process and analyze data efficiently. This project is suitable for applications involving large-scale text analysis and retrieval.

## Features

- **Data Preparation**: Processes knowledge base files and extracts meaningful content.
- **Embedding Generation**: Utilizes Hugging Face and Sentence Transformers for high-quality embeddings.
- **Vector Database**: FAISS for efficient vector storage and retrieval.
- **Retrieval-Augmented Generation**: Combines retrieved knowledge with generative AI models.
- **Customizability**: Modular design allows for easy adaptation to various datasets and use cases.

## Requirements

- Python 3.8 or later
- Libraries:
  - numpy
  - os
  - PyMuPDF
  - transformers
  - sentence-transformers
  - faiss-cpu
  - numpy
  - langchain
  - nltk
  - sklearn
  - google.generativeai

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-repo/rag-dream-islands.git
   cd rag-dream-islands
   ```

2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Ensure all dependencies are properly installed.

## Usage

1. Prepare your dataset and store it in the `data/` directory.
2. Run the script to process the data and generate embeddings:
   ```bash
   python rag_dream_islands_eng_new.py
   ```
3. Follow the output instructions for using the retrieval and generation pipeline.
4. To use the generation part a Google AI Studio API key is required. 
# dream_islands_RAG
Repository for the Travel Project Dream Islands
