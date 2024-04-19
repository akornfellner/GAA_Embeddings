# Vectors and Embeddings Presentation

This repository contains a Jupyter notebook that serves as a presentation on vectors and embeddings. The presentation is designed to provide a comprehensive understanding of vectors, their operations, and how they are used in the field of machine learning, specifically in embeddings.

## Table of Contents

1. **Introduction to Vectors**
    - Definition and representation of vectors
    - Vector operations: norm, normalization, and dot product
    - Angle between vectors and cosine similarity
    - Extension to higher dimensions

2. **Introduction to Embeddings**
    - Definition and use-cases of embeddings
    - Text embeddings using OpenAI's text-embedding-3-large model

3. **Practical Examples**
    - Calculation of vector operations using Numpy
    - Visualization of vectors
    - Calculation of text embeddings using OpenAI's API

## Setup

To run the notebook, you will need to install the required Python libraries. You can do this by running the following command:

```bash
pip install -r requirements.txt
```

You will also need to set up an OpenAI account and obtain an API key to use the text-embedding-3-large model. Once you have the API key, you can set it as an environment variable:

```bash
export OPEN_AI_API_KEY=your_api_key
```

## Usage

You can start the Jupyter notebook by running the following command:

```bash
jupyter notebook Embedding.ipynb
```

Then, you can go through the notebook, running each cell in order to follow along with the presentation.

## License

This project is licensed under the terms of the MIT license.

